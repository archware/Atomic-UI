---
title: "Política de seguridad y protección de activos de Atomic UI"
author: "Ing. Havel CONTRERAS TAPAHUASCO"
date: "2026-11-21"
last_updated: "2026-11-21"
version: "1.0.0"
change_id: "DOC-20261121-001"
document_type: "política de seguridad"
status: "vigente"
---

# Política de seguridad y protección de activos

## 1. Endurecimiento de la vitrina pública

La distribución pública desplegada en este repositorio contiene exclusivamente activos estáticos compilados y minificados generados por Azure Pipelines. Antes de cada publicación se verifica:

1. La supresión de código fuente, plantillas y hojas de estilo en los metadatos de documentación (`--disableSourceCode`).
2. La desactivación y eliminación recursiva de mapas de origen (`devtool: false` y purga de archivos `*.map`).
3. La ausencia total de credenciales, tokens internos o rutas de infraestructura privada.

## 2. Reporte de vulnerabilidades

Cualquier hallazgo de seguridad relacionado con la vitrina pública o con los componentes compilados debe notificarse por correo electrónico a `havel363@gmail.com`.
