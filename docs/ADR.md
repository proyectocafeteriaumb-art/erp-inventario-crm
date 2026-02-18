# ADR 1: Lenguaje de programación
Decisión: Se utilizará **C#** para el backend con **ASP.NET Core**, y **Blazor** para el frontend (web), aprovechando el ecosistema de Microsoft.

# ADR 2: Patrón arquitectónico
Decisión: Se adopta **arquitectura hexagonal**, separando UI, dominio y persistencia, para facilitar mantenibilidad y escalabilidad.

# ADR 3: Persistencia y base de datos
Decisión: Se utilizará **SQL Server** como base de datos principal, integrándose con Entity Framework Core para el acceso a datos.

# ADR 4: Estrategia de autenticación
Decisión: Se implementará **autenticación con JWT** y roles definidos, integrando IdentityServer o ASP.NET Core Identity para la seguridad de usuarios.

