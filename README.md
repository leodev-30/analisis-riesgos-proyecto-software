# Análisis de Riesgos y Seguridad - Proyecto de Software (Java / H5P)

Este repositorio contiene la documentación y la matriz de gestión de riesgos aplicada a un proyecto de desarrollo de software académico y colaborativo, utilizando principios de metodologías formales como **OCTAVE** y **Magerit**.

## 👥 Contexto del Proyecto
* **Equipo de Desarrollo:** 4 integrantes.
* **Stack Tecnológico:** Java, módulos H5P y control de versiones en la nube.
* **Partes Interesadas (Stakeholders):** Profesores y directivos de la institución educativa.

---

## 📊 Matriz de Evaluación de Riesgos (CID)
Se identificaron los activos críticos del proyecto (humanos, de información y servicios), evaluándolos bajo la triada de seguridad **CID** (Confidencialidad, Integridad y Disponibilidad), determinando su criticidad resultante y definiendo el tratamiento y riesgo residual tras aplicar salvaguardas (MFA, respaldos, control de accesos y acuerdos).

><img width="1410" height="530" alt="image" src="https://github.com/user-attachments/assets/0e0e4e9c-a24c-44c8-bbc7-3ebf65fac7f9" />

---

## 🛡️ Principales Salvaguardas Implementadas
1. **Para Módulos de Código y GitHub:**
   * Implementación de Autenticación Multifactor (MFA).
   * Copias de seguridad automáticas y control de cambios riguroso.
   * Reducción del riesgo a un nivel **Asumido (Bajo Z1)**.
2. **Para el Personal y Requerimientos:**
   * Aplicación del principio de **mínimo privilegio** en los accesos.
   * Cláusulas de permanencia y acuerdos de responsabilidad para el equipo de desarrollo.
   * Uso de funciones hash para garantizar la integridad de la información y requerimientos.

---
## 🎯 Conclusión
La aplicación de este análisis permitió identificar las vulnerabilidades operativas y técnicas del entorno de desarrollo, demostrando cómo la implementación de controles proporcionales reduce el riesgo crítico inicial a zonas de aceptación controlada por la dirección del proyecto.
