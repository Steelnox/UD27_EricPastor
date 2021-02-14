# UD27_EricPastor_Ej1


#### 1. Description
```
Demo API REST creada con .NET COre 3.1 utilizando varias entidades ER y conectada con base de datos 
MS Sql Virtualizada sobre Fedora 32  y Virtualbox 6.1. Aplicación con fines educativos.
```

#### 2. Link a un demo con el proyecto desplegado: https://github.com/Steelnox/UD27_EricPastor

```
* Nombre de la App: [GIT] (https://github.com/)
```
#### 3. Lista con los pasos mínimos que se necesitan para clonar exitosamente el proyecto y echarlo a andar en local.

###### Install
```
IDE               Visual Studio 2019 Community Version
Core              C# 
Framework         NET Core 3.1
DataBase          Microsoft Sql Server 
Virtual           VirtualBox 6.1
SO                Fedora 32
```
###### packages Nuget 
```
Install-Package Microsoft.VisualStudio.Web.CodeGeneration.Design  -Version 3.1.4
Install-Package Microsoft.EntityFrameworkCore.Tools               -Version 3.1.8
Install-Package Microsoft.EntityFrameworkCore.SqlServer           -Version 3.1.8
```
###### Cadena de Conexión Base de datos 
```
"AllowedHosts": "*",
    "ConnectionStrings": {
        "DatabaseConnection": "Server=192.168.0.29;Database=UD27_Ej1;User ID=Eric; Password=Root_1234"
    }
```
#### 4. URIs endpoints.
```
Piezas
GET       /api/Piezas
POST      /api/Piezas
GET       /api/Piezas/{id}
PUT       /api/Piezas/{id}
DELETE    /api/Piezas/{id}

Proveedores
GET       /api/Proveedores
POST      /api/Proveedores
GET       /api/Proveedores/{id}
PUT       /api/Proveedores/{id}
DELETE    /api/Proveedores/{id}

Suministras
GET       /api/Suministras
POST      /api/Suministras
GET       /api/Suministras/{id}
PUT       /api/Suministras/{id}
DELETE    /api/Suministras/{id}
```

#### 5. Screenshot imagen que indique cómo debe verse el proyecto.
![image](https://user-images.githubusercontent.com/11030691/107878815-5b131a00-6ed5-11eb-9729-6044e9e6c177.png)


# UD27_EricPastor_Ej2


#### 1. Description
```
Demo API REST creada con .NET COre 3.1 utilizando varias entidades ER y conectada con base de datos 
MS Sql Virtualizada sobre Fedora 32  y Virtualbox 6.1. Aplicación con fines educativos.
```

#### 2. Link a un demo con el proyecto desplegado: https://github.com/Steelnox/UD27_EricPastor

```
* Nombre de la App: [GIT] (https://github.com/)
```
#### 3. Lista con los pasos mínimos que se necesitan para clonar exitosamente el proyecto y echarlo a andar en local.

###### Install
```
IDE               Visual Studio 2019 Community Version
Core              C# 
Framework         NET Core 3.1
DataBase          Microsoft Sql Server 
Virtual           VirtualBox 6.1
SO                Fedora 32
```
###### packages Nuget 
```
Install-Package Microsoft.VisualStudio.Web.CodeGeneration.Design  -Version 3.1.4
Install-Package Microsoft.EntityFrameworkCore.Tools               -Version 3.1.8
Install-Package Microsoft.EntityFrameworkCore.SqlServer           -Version 3.1.8
```
###### Cadena de Conexión Base de datos 
```
"AllowedHosts": "*",
    "ConnectionStrings": {
        "DatabaseConnection": "Server=192.168.0.29;Database=UD27_Ej2;User ID=Eric; Password=Root_1234"
    }
```
#### 4. URIs endpoints.
```
Cientificos
GET       /api/Cientificos
POST      /api/Cientificos
GET       /api/Cientificos/{id}
PUT       /api/Cientificos/{id}
DELETE    /api/Cientificos/{id}

Proyectos
GET       /api/Proyectos
POST      /api/Proyectos
GET       /api/Proyectos/{id}
PUT       /api/Proyectos/{id}
DELETE    /api/Proyectos/{id}

Asignados_a
GET       /api/Asignados_a
POST      /api/Asignados_a
GET       /api/Asignados_a/{id}
PUT       /api/Asignados_a/{id}
DELETE    /api/Asignados_a/{id}
```

#### 5. Screenshot imagen que indique cómo debe verse el proyecto.
![image](https://user-images.githubusercontent.com/11030691/107881387-70437500-6ee4-11eb-9587-9fae2768dcc1.png)

# UD27_EricPastor_Ej3


#### 1. Description
```
Demo API REST creada con .NET COre 3.1 utilizando varias entidades ER y conectada con base de datos 
MS Sql Virtualizada sobre Fedora 32  y Virtualbox 6.1. Aplicación con fines educativos.
```

#### 2. Link a un demo con el proyecto desplegado: https://github.com/Steelnox/UD27_EricPastor

```
* Nombre de la App: [GIT] (https://github.com/)
```
#### 3. Lista con los pasos mínimos que se necesitan para clonar exitosamente el proyecto y echarlo a andar en local.

###### Install
```
IDE               Visual Studio 2019 Community Version
Core              C# 
Framework         NET Core 3.1
DataBase          Microsoft Sql Server 
Virtual           VirtualBox 6.1
SO                Fedora 32
```
###### packages Nuget 
```
Install-Package Microsoft.VisualStudio.Web.CodeGeneration.Design  -Version 3.1.4
Install-Package Microsoft.EntityFrameworkCore.Tools               -Version 3.1.8
Install-Package Microsoft.EntityFrameworkCore.SqlServer           -Version 3.1.8
```
###### Cadena de Conexión Base de datos 
```
"AllowedHosts": "*",
    "ConnectionStrings": {
        "DatabaseConnection": "Server=192.168.0.29;Database=UD27_Ej3;User ID=Eric; Password=Root_1234"
    }
```
#### 4. URIs endpoints.
```
Cajeros
GET       /api/Cajeros
POST      /api/Cajeros
GET       /api/Cajeros/{id}
PUT       /api/Cajeros/{id}
DELETE    /api/Cajeros/{id}

Productos
GET       /api/Productos
POST      /api/Productos
GET       /api/Productos/{id}
PUT       /api/Productos/{id}
DELETE    /api/Productos/{id}

Maquinas_registradoras
GET       /api/Maquinas_registradoras
POST      /api/Maquinas_registradoras
GET       /api/Maquinas_registradoras/{id}
PUT       /api/Maquinas_registradoras/{id}
DELETE    /api/Maquinas_registradoras/{id}

Venta
GET       /api/Venta
POST      /api/Venta
GET       /api/Venta/{id}
PUT       /api/Venta/{id}
DELETE    /api/Venta/{id}
```

#### 5. Screenshot imagen que indique cómo debe verse el proyecto.
![image](https://user-images.githubusercontent.com/11030691/107883441-43e12600-6eef-11eb-9425-93162e455513.png)

# UD27_EricPastor_Ej4


#### 1. Description
```
Demo API REST creada con .NET COre 3.1 utilizando varias entidades ER y conectada con base de datos 
MS Sql Virtualizada sobre Fedora 32  y Virtualbox 6.1. Aplicación con fines educativos.
```

#### 2. Link a un demo con el proyecto desplegado: https://github.com/Steelnox/UD27_EricPastor

```
* Nombre de la App: [GIT] (https://github.com/)
```
#### 3. Lista con los pasos mínimos que se necesitan para clonar exitosamente el proyecto y echarlo a andar en local.

###### Install
```
IDE               Visual Studio 2019 Community Version
Core              C# 
Framework         NET Core 3.1
DataBase          Microsoft Sql Server 
Virtual           VirtualBox 6.1
SO                Fedora 32
```
###### packages Nuget 
```
Install-Package Microsoft.VisualStudio.Web.CodeGeneration.Design  -Version 3.1.4
Install-Package Microsoft.EntityFrameworkCore.Tools               -Version 3.1.8
Install-Package Microsoft.EntityFrameworkCore.SqlServer           -Version 3.1.8
```
###### Cadena de Conexión Base de datos 
```
"AllowedHosts": "*",
    "ConnectionStrings": {
        "DatabaseConnection": "Server=192.168.0.29;Database=UD27_Ej4;User ID=Eric; Password=Root_1234"
    }
```
#### 4. URIs endpoints.
```
Investigadores
GET       /api/Investigadores
POST      /api/Investigadores
GET       /api/Investigadores/{id}
PUT       /api/Investigadores/{id}
DELETE    /api/Investigadores/{id}

Facultades
GET       /api/Facultades
POST      /api/Facultades
GET       /api/Facultades/{id}
PUT       /api/Facultades/{id}
DELETE    /api/Facultades/{id}

Equipos
GET       /api/Equipos
POST      /api/Equipos
GET       /api/Equipos/{id}
PUT       /api/Equipos/{id}
DELETE    /api/Equipos/{id}

Reservas
GET       /api/Reservas
POST      /api/Reservas
GET       /api/Reservas/{id}
PUT       /api/Reservas/{id}
DELETE    /api/Reservas/{id}
```

#### 5. Screenshot imagen que indique cómo debe verse el proyecto.
![image](https://user-images.githubusercontent.com/11030691/107884420-49416f00-6ef5-11eb-8aff-44359c235cd0.png)

