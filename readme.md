# API Clientes - SONDA

Taller para el desarrollo simple de una API en .NET Core 2 con Entity Framework.

**Herramientas necesarias:**
 - Visual Studio 2017 (Con .NET Core 2)
 - NET Core 2.1 SDK
 - Postman
 - SQL Server (opcional)
 ---

|Verbo|URI|Descripción|
|--|--|--|
|*GET*|cliente|Obtiene todos los clientes que están registrados en el sistema|
|*GET*|cliente/:rut|Obtiene los datos del cliente especificando el RUT|
|*POST*|cliente|Ingresar un nuevo cliente|
|*DELETE*|cliente/:rut|Elimina un cliente especificando el RUT|


## Fuentes

> **EF Core**: https://docs.microsoft.com/es-es/ef/core/
