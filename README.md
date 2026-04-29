# Laboratorio Crud Rapido utilizando laravel
![](https://i.ibb.co/rGM2rKPg/5-80.avif)

### Requisitos necesarios para la realizacion del laboratorio:
- PHP versión 8.0 o superior.
- Composer última versión estable.
- Laravel Installer o crear proyecto con laravel new / composer create-project.
- Paquete de servidor web local. (Entorno de Desarrollo)(ej.
XAMPP, WampServer o Laragon).
- Servidor web: Apache o Nginx
- Base de datos MySQL/MariaDB funcionando.
- Editor de código (Visual Studio Code recomendado).
- Sistema Operativo: windows, MacOs
- Instalación de dependencias con composer install y configuración del
archivo .env.
- Utilizacion de comandos necesarios para las migraciones e instalaciones


## Introduccion
En este laboratorio realizaremos multiples migraciones a una base de datos llamada crud_rapido, utilizando multiples comandos, y usos de controladores de una API, para el uso correcto de todos estos, teniendo una pagina de login, registro y products que es la que se encargaria de manejar los productos, el stock, su precio y descripcion.

Durante este laboratorio para la realizacion las migraciones los codigos utilizados fueron:

1 - Install

* composer require ibex/crud-generator --dev
* php artisan vendor:publish --tag=crud
* composer require ibex/crud-generator:1.6 --dev

## Resultados obtenidos

#### Ejecución del código
![Ejecución del código](https://i.ibb.co/t1HC6VZ/Ejecucion-de-codigo.png)

#### Ejecución del código (continuación)
![Ejecución del código 1](https://i.ibb.co/Myc93fGr/Ejecucion-de-codigo-1.png)

![Ejecución del código 2](https://i.ibb.co/wFxBbmfc/Ejecucion-de-codigo-2.png)

![Ejecución del código 3](https://i.ibb.co/QjQkRyrh/Ejecucion-de-codigo-3.png)

![Ejecución del código 4](https://i.ibb.co/VWn9sL8J/Ejecucion-de-codigo-4.png)

![Ejecución del código 5](https://i.ibb.co/LD8bBnwt/Ejecucion-de-codigo-5.png)

#### Resultados finales

![Resultado 1](https://i.ibb.co/0pVwF5fd/Resultado-1.png)

![Resultado 2](https://i.ibb.co/rGJSGJwN/Resultado-2.png)

![Resultado 3](https://i.ibb.co/KpYLyXGY/Resultado-3.png)

![Resultado 4](https://i.ibb.co/hFHf2pyy/Resultado-4.png)


## Base de datos

La base de datos llamada crud_rapido contiene la informacion de los usuarios, los inicios de sesion realizados,las migraciones que se han hecho y los productos que se han registrado.

![Base de datos](https://i.ibb.co/GvmqCK5f/BD1.png)
* Como podemos observar esta contiene multiples tablas que contienen informacion, las migraciones, contraseñas basadas en tokens, sesiones, productos, etc.


En el momento que se hacen las migraciones anterior a esto se tienen que hacer las modificaciones al archivo **.env** que es aquel que contiene la informacion del usuario y contraseña que tendremos en mysql de igual manera controla el servidor, el logeo y todo lo necesario para iniciar el servicio.

El codigo a modificar seria esta seccion

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=crud_rapido
DB_USERNAME=root
DB_PASSWORD=
```
## Documentación utilizada

- [Repositorio Laravel CRUD Generator](https://github.com/awais-vteams/laravel-crud-generator)
- [Video sobre Laravel CRUD Generator](https://www.youtube.com/watch?v=j5baJsM_Adc&t=111s)
###

## Información del Estudiante

<div align="center">
  <img src="https://i.ibb.co/hRsj2N6J/91-logo-5-fisc-oficial-rgb.png" alt="FISC" width="200"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://i.ibb.co/3yhkfK7X/6-logo-utp-rgb-oficial.png" alt="UTP" width="200"/>
</div>

<br>

Este laboratorio ha sido desarrollado por el estudiante **Solín Antonio Rodrigúez** de la Universidad Tecnológica de Panamá:

- **Nombre:** Solín Antonio Rodrigúez  
- **Correo:** solin.rodriguez@utp.ac.pa  
