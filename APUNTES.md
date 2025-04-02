# CURSO .NET

Repaso .NET CORE
¡Claro! Aquí tienes una guía paso a paso para repasar .NET Core:
1.	Instalación y Configuración:
o	Asegúrate de tener instalado .NET Core SDK. Puedes descargarlo desde el sitio oficial de Microsoft.
2.	Fundamentos de ASP.NET Core:
o	Revisa cómo crear una aplicación web básica con ASP.NET Core.
o	Explora la estructura de proyectos y cómo funciona el ciclo de vida de una solicitud HTTP.
3.	Inyección de Dependencias (DI):
o	Estudia cómo registrar y resolver servicios en el contenedor de DI.
o	Practica la inyección de dependencias en controladores y servicios.
4.	Configuración y Entornos:
o	Aprende a usar el archivo appsettings.json y variables de entorno para configuraciones específicas.
5.	Middleware:
o	Investiga cómo funciona el pipeline de middleware y cómo personalizarlo para manejar solicitudes HTTP.
6.	Entity Framework Core:
o	Practica operaciones CRUD y cómo trabajar con migraciones en Entity Framework Core.
7.	Práctica y Proyectos:
o	Intenta crear un proyecto simple que utilice varios de estos conceptos.
8.	Recursos Adicionales:
o	Utiliza documentación oficial, tutoriales en línea, y videos para reforzar lo que aprendes.

ARCHIVO Index.cshtml
<div>
    @{
        ViewData["Title"] = "Home Page";
    }
    CLASE 1:
    <div>    
        <h1>ALINEACION DE FILAS Y COLUMNAS</h1>
        <h4>Ejemplo 1: Alineando la fila</h4>
        <div class="row align-items-start">
            <div class="col">
                Columna 1
            </div>
            <div class="col">
                Columna 2
            </div>
            <div class="col">
                Columna 3
            </div>
        </div>
        <div class="row align-items-center">
            <div class="col">
                Columna 1
            </div>
            <div class="col">
                Columna 2
            </div>
            <div class="col">
                Columna 3
            </div>
        </div>
        <div class="row align-items-end">
            <div class="col">
                Columna 1
            </div>
            <div class="col">
                Columna 2
            </div>
            <div class="col">
                Columna 3
            </div>
        </div>
        <h4>Ejemplo 2: Alineando las columnas horizontalmente</h4>
        <div class="row">
            <div class="col align-self-start">
                Columna 1
            </div>
            <div class="col align-self-center">
                Columna 2
            </div>
            <div class="col align-self-end">
                Columna 3
            </div>
        </div>
        <h4>Ejemplo 3: Offset</h4>
        <div class="row">
            <div class="col-4">
                Columna 1
            </div>
            <div class="col-4 offset-1">
                Columna 2
            </div>
        </div>
        <h4>Ejemplo 4: Auto Margen</h4>
        <div class="row">
            <div class="col-4">
                Columna 1
            </div>
            <div class="col-4 ms-auto">
                Columna 2
            </div>
        </div>
    </div>
    CLASE 2
    <div>
        <h1>ESPACIO ENTRE COLUMNAS Y FILAS</h1>
        <h4>Ejemplo 1: Gutter Horizontal</h4>
        <div class="row gx-sm-0 gx-md-3 gx-lg-5">
            <div class="col">
                <div class="bg-light border">
                    Columna 1
                </div>
            </div>
            <div class="col">
                <div class="bg-light border">
                    Columna 2
                </div>
            </div>
        </div>
        <h4>Ejemplo 2: Gutter Vertical</h4>
        <div class="row gx-sm-0 gx-md-3 gx-lg-5 gy-3">
            <div class="col-6">
                <div class="bg-light border">
                    Columna 1
                </div>
            </div>
            <div class="col-6">
                <div class="bg-light border">
                    Columna 2
                </div>
            </div>
            <div class="col-6">
                <div class="bg-light border">
                    Columna 3
                </div>
            </div>
            <div class="col-6">
                <div class="bg-light border">
                    Columna 4
                </div>
            </div>
        </div>
        <h4>Ejemplo 2: Gutter Horizontal y Vertical</h4>
        <div class="row g-3">
            <div class="col-6">
                <div class="bg-light border">
                    Columna 1
                </div>
            </div>
            <div class="col-6">
                <div class="bg-light border">
                    Columna 2
                </div>
            </div>
            <div class="col-6">
                <div class="bg-light border">
                    Columna 3
                </div>
            </div>
            <div class="col-6">
                <div class="bg-light border">
                    Columna 4
                </div>
            </div>
        </div>
    </div>
    CLASE 3
    <div>
        <h4>Ejemplo 1: Imagenes en columnas</h4>
        <div class="row gy-3">
            <div class="col-sm-3">
                <img class="img-fluid" src="https://i.ytimg.com/vi/BiGxom_UD80/sddefault.jpg?v=61953b5a" />
            </div>
            <div class="col-sm-3">
                <img class="img-fluid" src="https://i.ytimg.com/vi/BiGxom_UD80/sddefault.jpg?v=61953b5a" />
            </div>
            <div class="col-sm-3">
                <img class="img-fluid" src="https://i.ytimg.com/vi/BiGxom_UD80/sddefault.jpg?v=61953b5a" />
            </div>
            <div class="col-sm-3">
                <img class="img-fluid" src="https://i.ytimg.com/vi/BiGxom_UD80/sddefault.jpg?v=61953b5a" />
            </div>
        </div>
        <h4>Ejemplo 2: Imagenes tipo thumbnail</h4>
        <img class="img-thumbnail rounded-circle" src="https://img.a.transfermarkt.technology/portrait/big/28003-1740766555.jpg?lm=1" />
        </div>
    </div>
    CLASE 4
    <div>
        <h4>Tabla con estilos de Bootstrap</h4>
        <table class="table table-striped table-hover table-bordered table-sm">
            <thead>
                <tr>
                    <th>#</th>
                    <th>Nombre</th>
                    <th>Apellido</th>
                </tr>
            </thead>
            <tbody>
                <tr class="table-success">
                    <td>1</td>
                    <td>Carlos</td>
                    <td>Sanchez</td>
                </tr>
                <tr class="table-dark">
                    <td>2</td>
                    <td>Jose</td>
                    <td>Rodriguez</td>
                </tr>
                <tr class="table-danger">
                    <td>3</td>
                    <td>Andres</td>
                    <td>Gomez</td>
                </tr>
            </tbody>
        </table>
    </div>
    CLASE 5
    <div>
        <div>
            Sin ratio
        </div>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/WpbBhTx5R9Q?si=CgBgQ0IxpjoQ3fe1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <div>
            Con ratio 16x9
        </div>
        <div class="ratio ratio-16x9">
            <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/WpbBhTx5R9Q?si=CgBgQ0IxpjoQ3fe1" allowfullscreen></iframe>
        </div>
        <hr />
        <div class="row gy-4">
            <div class="col-md-4">
                <div class="ratio ratio-16x9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/WpbBhTx5R9Q?si=CgBgQ0IxpjoQ3fe1" allowfullscreen></iframe>
                </div>
            </div>
            <div class="col-md-4">
                <div class="ratio ratio-16x9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/WpbBhTx5R9Q?si=CgBgQ0IxpjoQ3fe1" allowfullscreen></iframe>
                </div>
            </div>
            <div class="col-md-4">
                <div class="ratio ratio-16x9">
                    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/WpbBhTx5R9Q?si=CgBgQ0IxpjoQ3fe1" allowfullscreen></iframe>
                </div>
            </div>
        </div>
    </div>
    CLASE 6
    <div>  
    </div>
    CLASE 7
    <div>    
    </div>
    CLASE 8
    <div>    
    </div>
    CLASE 9
    <div>    
    </div>
    CLASE 10
    <div>    
    </div>
    CLASE 11
    <div>    
    </div>
    CLASE 12
    <div>    
    </div>
    CLASE 13
    <div>    
    </div>
</div>