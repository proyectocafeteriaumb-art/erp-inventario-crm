# ADR – Módulo CRM

## 1️⃣ Título
Decisión de arquitectura para la implementación del módulo CRM

---

## 2️⃣ Contexto
El módulo CRM forma parte del ERP y debe permitir:
- Gestión de clientes (CRUD)  
- Gestión de oportunidades de venta  
- Registro de interacciones con clientes  
- Dashboard con métricas y reportes  
- Integración con base de datos y otros módulos del ERP  

Se requiere definir cómo se estructurará el backend, la comunicación entre componentes y la forma de manejar los datos, asegurando **mantenibilidad, escalabilidad y facilidad de pruebas**.

---

## 3️⃣ Decisión
Se decidió implementar la arquitectura **Controller → Service → Repository**:  

- **Controller:** Maneja las rutas y solicitudes HTTP, valida datos básicos y devuelve respuestas.  
- **Service:** Contiene la lógica de negocio principal, coordinando operaciones entre repositorios y otros servicios.  
- **Repository:** Acceso a base de datos (CRUD) para clientes, oportunidades e interacciones.  

Además:
- Se usarán **branches por historia de usuario** (`feat/<nombre-historia>`) para desarrollo independiente.  
- Se implementarán **tests unitarios y de integración** desde el inicio.  
- Los diagramas PlantUML documentarán la arquitectura y flujo del módulo.  

---

## 4️⃣ Alternativas consideradas
1. **Arquitectura monolítica simple sin capas:**  
   - Pros: Más rápido de implementar.  
   - Contras: Difícil de mantener, difícil de testear y extender.  

2. **Microservicios independientes por cada entidad (Clientes, Oportunidades, Interacciones):**  
   - Pros: Escalable, cada servicio independiente.  
   - Contras: Mayor complejidad inicial, overhead en comunicación, no necesario para módulo pequeño.  

3. **Arquitectura Controller-Service-Repository (elegida):**  
   - Pros: Equilibrio entre modularidad y simplicidad.  
   - Fácil de mantener y testear.  
   - Compatible con futuros microservicios si se decide escalar.  

---

## 5️⃣ Consecuencias
- La modularidad permite **cambios sin afectar todo el módulo**.  
- Se puede probar cada capa de forma independiente.  
- Facilita la documentación y visualización con PlantUML.  
- El código sigue buenas prácticas y es más escalable para futuros desarrollos.  
- Requiere disciplina en la creación de branches y pruebas antes de merge.  

---

✅ **Notas:**
- Este ADR debe actualizarse si en el futuro se decide migrar a microservicios o cambiar la base de datos.  
- Todas las historias de usuario del CRM deben seguir esta arquitectura y documentarse según DoR y DoD.  
