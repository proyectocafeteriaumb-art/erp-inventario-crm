# Sprint Planning 1 – Módulo CRM

## 1️⃣ Objetivo del Sprint 1
Implementar las funcionalidades básicas del módulo CRM para iniciar pruebas internas:  
- Gestión de clientes  
- Gestión de oportunidades  
- Registro de interacciones  
- Dashboard inicial con métricas básicas  

---

## 2️⃣ Sprint Backlog

| Historia de usuario | Prioridad | Estimación (puntos) | Branch asignada | Estado |
|--------------------|-----------|--------------------|----------------|--------|
| Como ejecutivo de ventas, quiero registrar nuevos clientes | Alta | 3 | feat/crear-clientes | Pendiente |
| Como ejecutivo de ventas, quiero editar clientes existentes | Alta | 2 | feat/editar-clientes | Pendiente |
| Como ejecutivo de ventas, quiero buscar clientes por nombre o email | Media | 2 | feat/buscar-clientes | Pendiente |
| Como ejecutivo de ventas, quiero registrar interacciones con clientes | Alta | 3 | feat/registro-interacciones | Pendiente |
| Como ejecutivo de ventas, quiero crear oportunidades de venta | Alta | 3 | feat/crear-oportunidades | Pendiente |
| Como ejecutivo de ventas, quiero actualizar el estado de las oportunidades | Media | 2 | feat/actualizar-oportunidades | Pendiente |
| Como gerente de cuentas, quiero ver el Dashboard inicial con métricas | Media | 3 | feat/dashboard-inicial | Pendiente |

---

## 3️⃣ Estimaciones

- Total de puntos del sprint: **18 puntos**  
- Sprint duration: **2 semanas**  
- Estimación basada en complejidad y dependencias:  
  - Funcionalidad CRUD simple → 2–3 puntos  
  - Dashboard y métricas → 3 puntos  
  - Integración con base de datos → incluidas dentro de cada historia  

---

## 4️⃣ Branches creadas

| Branch | Descripción |
|--------|-------------|
| `feat/crear-clientes` | Implementa registro de nuevos clientes |
| `feat/editar-clientes` | Implementa edición de clientes existentes |
| `feat/buscar-clientes` | Implementa búsqueda de clientes |
| `feat/registro-interacciones` | Implementa registro de interacciones |
| `feat/crear-oportunidades` | Implementa creación de oportunidades |
| `feat/actualizar-oportunidades` | Implementa actualización de estado de oportunidades |
| `feat/dashboard-inicial` | Implementa Dashboard con métricas básicas |

---

## 5️⃣ Tareas técnicas

### Clientes
- [ ] Crear tabla `Clientes` en base de datos  
- [ ] Implementar `ClienteController` y rutas CRUD  
- [ ] Implementar `ClienteService` con lógica de negocio  
- [ ] Crear tests unitarios para clientes  

### Oportunidades
- [ ] Crear tabla `Oportunidades` en base de datos  
- [ ] Implementar `OportunidadController` y rutas CRUD  
- [ ] Implementar `OportunidadService` con lógica de negocio  
- [ ] Crear tests unitarios para oportunidades  

### Interacciones
- [ ] Crear tabla `Interacciones` en base de datos  
- [ ] Implementar `InteraccionController` y rutas CRUD  
- [ ] Implementar `InteraccionService` con lógica de negocio  
- [ ] Crear tests unitarios para interacciones  

### Dashboard
- [ ] Crear endpoints de métricas (clientes recientes, oportunidades abiertas)  
- [ ] Implementar componente de visualización básica en frontend  
- [ ] Crear tests de integración para Dashboard  

---

## 6️⃣ Ejecución

- Cada historia de usuario será desarrollada en su branch correspondiente  
- Se hará **merge a main** solo después de pruebas unitarias y de integración exitosas  
- Se realizará **Daily Standup** para seguimiento de tareas  
- Revisión final y demo al final del sprint  

---

✅ Este Markdown te deja **todo listo para documentar Sprint 1**: backlog, estimaciones, branches y tareas técnicas organizadas.  

---

Si quieres, puedo hacer **una versión visual tipo tablero Kanban**, con cada historia como tarjeta y su branch/tarea técnica, lista para tu presentación o Notion.  

¿Quieres que haga eso?
