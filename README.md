<p align="center">
  <a href="https://www.gatsbyjs.com">
    <img alt="PagoEfectivo" src="https://prod.cds.pagoefectivo.g3c.pe/img/general/pagoefectivo-footer.png" width="80" />
  </a>
</p>
<h1 align="center">
  Backend Technical Test - PagoEfectivo
</h1>

_:checkered_flag: La siguiente prueba trata sobre de construir una aplicación para códigos de promoción,
donde se deben tener las siguientes consideraciones:_

1. **Crear un API REST para generar un codigo de promocion**

    - Para generar un código se debe proporcionar nombre y email.
    - Solo se puede generar un código por email.
    - El codigo de promoción debe tener estados (generado y canjeado)

1. **Crear un API REST para canjear codigo de promoción**

    - Solo se puede canjear un código a la vez.

1. **Crear una interfaz para la gestión de los codigos de promoción**

    - Interfaz para gestionar el proceso de generación de códigos.
    - Interfaz para gestionar el proceso canje de códigos.
    - Interfaz para listar email registrados con códigos generados y estado de canje (email, nombre, código, estado).
    > Las interfaces pueden desarrollarse en Blazor, ASP.NET, React u otros (a elección).

___

### :clipboard: El desarrollo debe ser implementado con:

1. .Net 5.0.
2. Docker.
3. Control de versiones con Git.
4. Base de datos PostgreSQL o SQL Server.
5. Principios SOLID/Clean Code
6. Pruebas Unitarias.

### :floppy_disk: Entregable

1. El proyecto debe ser subido a github.
2. El proyecto debe contar con un README.md que contenga las instrucciones para iniciar la aplicación.
