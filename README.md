# UD27_EricPastor

1. Description
Demo API REST creada con .NET COre 3.1 utilizando varias entidades ER y conectada con base de datos 
MS Sql Virtualizada sobre Fedora 32  y Virtualbox 6.1. Aplicación con fines educativos.
2. Link a un demo con el proyecto desplegado: https://github.com/Steelnox/UD27_EricPastor
* Nombre de la App: [GIT] (https://github.com/)
3. Lista con los pasos mínimos que se necesitan para clonar exitosamente el proyecto y echarlo a andar en local.
Install
IDE               Visual Studio 2019 Community Version
Core              C# 
Framework         NET Core 3.1
DataBase          Microsoft Sql Server 
Virtual           VirtualBox 6.1
SO                Fedora 32
packages Nuget
Install-Package Microsoft.VisualStudio.Web.CodeGeneration.Design  -Version 3.1.4
Install-Package Microsoft.EntityFrameworkCore.Tools               -Version 3.1.8
Install-Package Microsoft.EntityFrameworkCore.SqlServer           -Version 3.1.8
Cadena de Conexión Base de datos
"AllowedHosts": "*",
    "ConnectionStrings": {
        "DatabaseConnection": "Server=192.168.0.29;Database=UD27_Ej1;User ID=Eric; Password=Root_1234"
    }
4. URIs endpoints.
Piezas
GET       /api/Piezas
POST      /api/Piezas
GET       /api/Piezas/{id}
PUT       /api/Piezas/{id}
DELETE    /api/Piezas/{id}

Proveedores
GET       /api/Videos
POST      /api/Videos
GET       /api/Videos/{id}
PUT       /api/Videos/{id}
DELETE    /api/Videos/{id}

Suministras
GET       /api/Suministras
POST      /api/Suministras
GET       /api/Suministras/{id}
PUT       /api/Suministras/{id}
DELETE    /api/Suministras/{id}

5. Screenshot imagen que indique cómo debe verse el proyecto.
