# Documentación MK 3
---

## Introduccion
El desarrollo se basa en un proyecto anterior llamado **MK2**. El cual se usa para la creación y consulta de reportes,
se decicidio migrar a laravel por ser un framework intuitivo y con muchas libreria y paquetes para agilizar el trabajo.

---

## Objetivo 
- El objetivo primordial es crear un nuevo proyecto con la finalidad de implemmnetar nuevos reportes.

---

## Estrutura del Desarrollo 
1. Para realizar la estructura del proyecto se vaso en su mayoria en la version anteriro  en el **MK2**,
la pagina principal se compone por un login el cual contiene dos perfiles los cuales son `Administrador` y `Operador`.

2. Dentro de la estructura principal se compone por 3 link en el menu de navegación los caules son **dashboard**, **reportes** y **nombre del usuario**, los cuales cumplen didsititas funciones.

### Dashboard
La cual esta parte se encarga de toda la parte administrativa del desarrollo y se encuntra en cards como: 

* [_Cambio de año_]: esta parte se encarda de cambiar el año el cual es necesario para ver un reporte.

* [_Usuarios_]: Se usa para `crear`, `eliminar`, `registrar`, `actualizar` a un usuario e incluyendo un reseteo de `contraseña`.

* [_costo de envio_]: Se usa para actualizar el costo de envio el cual se usa para la creación del pdf de ***Orden surtido por fecha***.

* [_Tabla de precios_]: A qui se carga un excel en especifo el cual contiene 8 columnas en especifico


**Ejemplo para subir excel**

| Estilo | Prenda | Precio vanity | Preico venta MK | Preico venta MK iva | diferencia participación | Margen | Descuento |
|--- |--- |--- | ---| ---| ---| ---| ---|
| 24008000 | Saco coral | $847 | $948 | 1100 | 100 | 10% | NO |

*[_Lista de estilos_]: aqui se dan de alta los estilos y el color que va relacionado cada estilo 

### Reportes

*[_Orden surtido_]: Se utiliza para solicitar informacion de un solo cliente.
 
*[_Orden surtido por fecha_]: Se utiliza para solicitar la infomacion de clientes por fecha.

*[_Clientes solicitan factura_]: Se encarga de brindar infomación de facturas por las fechas requeridas.

*[_Reportes Participación_]: Esta seccion se usa solo por parte del `Administrador`.

*[_Reportes formas de pago_]: Esta seccion solo muetra los metodos de pagos por fechas.

---

## Tegnologias utilizadas 
* **Laravel 8.1** [mas información](https://laravel.com/)
* **Axios** [mas información](https://axios-http.com/es/docs/intro)
* **javascript**
* **Sweetalert2** [mas información](https://sweetalert2.github.io/)
* **Bootstrap 5 v5.3** [mas información](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
* **Jquery-3.6.4** [mas información](https://releases.jquery.com/)
* **Fontawesome** [mas información](https://fontawesome.com/)

---

***Libreria de laravel y paquetes ***
>Laravel ui [link](https://diegooo.com/laravel-ui-autenticacion-de-laravel-8/)

>tightencoziggy [link](https://styde.net/acceder-a-las-rutas-de-laravel-desde-javascript-con-tightencoziggy/)     

>Laravel excel [link](https://laravel-excel.com/)     

>Laravel Dompdf [link](https://laravel-excel.com/)     


---

## Base de datos 
>[Actualmente el proyecto se encuentra conectado a 3 bases mas Todas se encuntran en **phpmyAdmin**]
### Diagrama
<img id="imgDiagrama"  src='/img/complemento_mk.svg'  alt="Diagrama" />

---
>Version del proyecto **1.0**