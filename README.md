﻿# SpendSmart

 SpendSmart

SpendSmart es una aplicación para la gestión inteligente de gastos personales. Permite a los usuarios realizar un seguimiento de sus gastos.

Características

Registro de gastos con detalles como descripcion y monto.


Tecnologías utilizadas

Backend: ASP.NET Core 8.0

Frontend: Razor Pages / MVC

Base de datos: SQL Server

ORM: Entity Framework Core


Pasos de instalación

Clonar el repositorio:

git clone https://github.com/emanuelbenitezbaez/SpendSmart.git

Navegar al directorio del proyecto:

cd SpendSmart

Restaurar paquetes NuGet:

dotnet restore

Configurar la base de datos en appsettings.json.

Aplicar migraciones:

dotnet ef database update

Ejecutar la aplicación:

dotnet run

Estructura del Proyecto

Controllers/: Controladores de la aplicación.

Models/: Modelos de datos.

Views/: Vistas de la aplicación.

wwwroot/: Archivos estáticos.

Program.cs: Punto de entrada de la aplicación.

Contribuir

Si deseas contribuir al proyecto, por favor sigue estos pasos:

Realiza un fork del repositorio.

Crea una rama con tu nueva funcionalidad: git checkout -b nueva-funcionalidad.

Realiza tus cambios y haz un commit: git commit -m 'Agrega nueva funcionalidad'.

Envía un pull request para su revisión.


