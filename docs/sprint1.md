# Sprint Planning 1 – Coffee Core ERP

## Objetivo del Sprint
Emitir una **orden de compra básica** con validación de stock.  
Al final del sprint, se debe poder generar una orden, verificar stock y registrar la transacción en el ERP.

---

## Sprint Backlog y Estimaciones

| Historia | Descripción | Story Points | Responsable |
|----------|------------|-------------|------------|
| Historia 1 | Crear/Actualizar productos | 5 | Frontend / Backend |
| Historia 2 | Generar orden de compra | 8 | Frontend / Backend |
| Historia 3 | Validación de stock | 3 | Backend / QA |

---

## Desglose técnico (tareas por historia)

| Historia | Tarea | Responsable | Tiempo Estimado |
|----------|------|------------|----------------|
| Historia 1 | Diseñar UI lista y formulario de producto | Frontend | 4h |
|          | Implementar backend CRUD productos | Backend | 6h |
|          | Pruebas unitarias | QA | 2h |
| Historia 2 | Crear formulario de orden | Frontend | 3h |
|          | Lógica de creación de orden | Backend | 5h |
|          | Validación de stock | Backend | 2h |
| Historia 3 | Implementar alertas de stock bajo | Backend | 2h |
|          | Pruebas integradas | QA | 2h |

---

## Plan de ramas

- `main` → rama estable  
- `dev` → integración de features  
- `feature/historia-1-crear-productos`  
- `feature/historia-2-orden-compra`  
- `feature/historia-3-validacion-stock`  

> **Nota:** Cada historia se desarrolla en su rama, se crea PR a `dev` y luego se mergea a `main` cuando esté aprobada.

---

## Criterios de Done (por historia)

- Funcionalidad implementada y testeada  
- PR revisada y aprobada  
- Demo funcional en entorno local  
- Actualización de diagramas y wireframes si cambian

---

