# Definition of Ready (DoR) y Definition of Done (DoD) – Módulo CRM

---

## 1️⃣ Definition of Ready (DoR)

Antes de que una historia de usuario pueda ser incluida en el sprint, debe cumplir los siguientes criterios:

- **Historia claramente definida**:  
  - Título descriptivo y conciso  
  - Descripción completa de la necesidad del usuario  
  - Criterios de aceptación claros y medibles  
- **Estimación realizada**:  
  - Puntos de historia asignados según complejidad  
- **Dependencias identificadas**:  
  - Recursos, APIs o datos necesarios disponibles  
  - Bloqueos documentados si existen  
- **Tareas técnicas preliminares**:  
  - Se identifican los endpoints, componentes y tests necesarios  
- **Aprobación del Product Owner**:  
  - Historia revisada y validada antes de pasar al sprint backlog  

---

## 2️⃣ Definition of Done (DoD)

Una historia de usuario se considera **completa** cuando cumple todos los siguientes criterios:

- **Código desarrollado y funcional**:  
  - Implementación de backend y frontend según los criterios de aceptación  
  - Integración con base de datos y otros módulos del CRM  
- **Pruebas realizadas**:  
  - Tests unitarios para todas las funciones nuevas  
  - Tests de integración si corresponde  
  - Todos los tests pasan correctamente  
- **Documentación completa**:  
  - Historia documentada en Jira/Notion  
  - Actualización de diagramas si aplica (PlantUML, wireframes)  
  - Tareas técnicas y endpoints documentados  
- **Código revisado y aprobado**:  
  - Pull request revisado por al menos un compañero  
  - Cumple normas de codificación del proyecto  
- **Despliegue listo**:  
  - Merge a main realizado sin conflictos  
  - Funcionalidad desplegada en entorno de pruebas  
- **Aceptación del Product Owner**:  
  - Historia revisada y validada como funcional según criterios de aceptación  

---

✅ **Notas adicionales:**

- Todas las historias de usuario deben pasar por **DoR antes de planificar el sprint**.  
- No se puede cerrar una historia hasta cumplir **DoD completo**.  
- DoR y DoD ayudan a mantener consistencia y calidad en cada incremento del módulo CRM.  
