# IISSI-2 IS: Simulacro de examen de laboratorio

## Enunciado

﻿
Enunciado Ordenación de productos por precio
Realice las modificaciones que considere necesarias, tanto en backend como en frontend, para satisfacer los nuevos requisitos que a continuación se describen. Se desea ofrecer a los propietarios que los productos de sus restaurantes aparezcan ordenados según el campo order de la entidad Producto o según el campo price del producto, y que puedan determinar cual será el orden predeterminado en cada restaurante, de manera que cuando se listen los productos aparezcan siempre según el orden que haya decidido.

Recuerde que actualmente los productos se muestran en la pantalla de detalle del restaurante y el backend los devuelve siempre ordenados según el campo order. Por defecto, cada restaurante ordenará sus productos según el mencionado campo order.

Implemente los cambios necesarios en Backend y Frontend para incluir dicha funcionalidad. Se espera que el Frontend siga un diseño como el que se muestra en las siguientes capturas.
Nótese que no se pide modificación de las pantallas de creación o edición de restaurante.

## Introducción

Este repositorio incluye el backend completo (carpeta `DeliverUS-Backend`) y el frontend de `owner` (carpeta `DeliverUS-Frontend-Owner`). Servirá como base para realizar el examen de laboratorio de la asignatura.

## Preparación del entorno

### a) Windows

* Abra un terminal y ejecute el comando `npm run install:all:win`.

### b) Linux/MacOS

* Abra un terminal y ejecute el comando `npm run install:all:bash`.

## Ejecución

### Backend

* Para **rehacer las migraciones y seeders**, abra un terminal y ejecute el comando

    ```Bash
    npm run migrate:backend
    ```

* Para **ejecutarlo**, abra un terminal y ejecute el comando

    ```Bash
    npm run start:backend
    ```

### Frontend

* Para **ejecutar la aplicación frontend de `owner`**, abra un nuevo terminal y ejecute el comando

    ```Bash
    npm run start:frontend:owner
    ```

## Depuración

* Para **depurar el backend**, asegúrese de que **NO** existe una instancia en ejecución, pulse en el botón `Run and Debug` de la barra lateral, seleccione `Debug Backend` en la lista desplegable, y pulse el botón de *Play*.

* Para **depurar el frontend**, asegúrese de que **EXISTE** una instancia en ejecución del frontend que desee depurar, pulse en el botón `Run and Debug` de la barra lateral, seleccione `Debug Frontend` en la lista desplegable, y pulse el botón de *Play*.

## Test

* Para comprobar el correcto funcionamiento de backend puede ejecutar el conjunto de tests incluido a tal efecto. Para ello ejecute el siguiente comando:

    ```Bash
    npm run test:backend
    ```
**Advertencia: Los tests no pueden ser modificados.**
