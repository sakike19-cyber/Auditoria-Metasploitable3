# Auditoría de Seguridad y Análisis de Vulnerabilidades - Metasploitable 3

Este repositorio contiene la documentación formal de la auditoría de seguridad realizada sobre un entorno controlado de pruebas (laboratorio virtual), utilizando herramientas estándar de la industria de la ciberseguridad.

## 👤 Información del Auditor
* **Nombre Completo:** Enrique Carlos Alfaro Huiñocana
* **Rol:** Auditor de Seguridad / Analista de Vulnerabilidades

## 📊 Resumen Ejecutivo del Escaneo
* **Herramienta Utilizada:** Tenable Nessus Essentials
* **Objetivo de la Evaluación:** Servidor Metasploitable 3 (Dirección IP: `192.168.145.131`)
* **Política de Escaneo:** Basic Network Scan
* **Duración:** 20 minutos
* **Total de Hallazgos:** 41 vulnerabilidades detectadas

### 🚨 Distribución de Severidad de Riesgos
* 🔴 **Críticas:** 2
* 🟠 **Altas:** 2
* 🟡 **Medias:** 9
* 🟢 **Bajas:** 4

---

## 🔍 Hallazgo Crítico Principal: Canonical Ubuntu Linux SEoL (14.04.x)
* **Severidad:** Máxima (Puntuación CVSS v3.0: **10.0**)
* **Descripción:** El sistema operativo de la máquina objetivo ha alcanzado el fin de su vida útil y no cuenta con soporte técnico ni parches de seguridad activos (*Supported End of Life*). Esto expone el servidor a múltiples vectores de ataque automatizados y exploits públicos.
* **Remediación:** Se recomienda una migración y actualización inmediata (*Upgrade*) a una versión con soporte de largo plazo vigente (LTS), como Ubuntu 22.04 o 24.04.

---

## 📁 Entregable Formal
El informe técnico completo con metodologías, descripciones detalladas de los fallos identificados y planes específicos de mitigación de riesgos se encuentra adjunto en este repositorio.

📌**[Descargar Reporte Formal en PDF](./Reporte_Auditoria_Metasploitable3_Formal.pdf)**
