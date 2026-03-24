# Vista de Contexto

Este diagrama muestra cómo interactúan los usuarios con el sistema.

```mermaid
graph TD
    Usuario[Usuario] -->|Autenticación| Auth[Módulo de Autenticación]
    Auth --> Sistema[Sistema Web]
    Sistema -->|Consulta| BD[Base de Datos]
    Sistema -->|Conecta| API[API Externa]
    Admin[Administrador] --> Sistema
