---
title: SL2100
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: July 16, 2016

sidebar: mydoc_sidebar
permalink: mydoc_release_notes_60.html
folder: mydoc
---

## MANUALES
Si desea ver los manuales completos de la SL2100 ingrese al link [Ver Manuales](https://drive.google.com/drive/folders/12A8vo8xROqJdaGIwD6x4NSJPwsDGlLmt?usp=sharing "Manuales SL2100")

## ACCEDER A LA PLANTA
Para ingresar a las configuraciones de la planta debe utilizar un browser y colocar la IP 172.16.0.10 donde se le pedirá ingresar las siguientes credenciales:

Usuario:tech
Password:12345678

## CONFIGURACIÓN DE EXTENSIONES
**Nombres:**
*  **15-01** Agregar nombre a las extensiones.

**Números (físicos/IP):**

**Restricciones:**

*  **21-04** Restricción de las extensiones(revisar tabla de permisos en 21-05).
*  **21-05** Restringir de acuerdo a los modos(revisar las restricciones de cada modo en 21-06).
*  **21-06** Se definen las restricciones de los modos (1,2,3,4,5). Para restringir llamadas internacionales anteponer 00 ó 1470, departamentales con 6 y 7, restringir todo con el símbolo de @.

**Otros:**

## CONFIGURACIÓN DE LINEAS CO

**Grupos:**


**Entrantes (E1 Pri):**


**Salientes (E1 SIP):**


**Restricciones:**


**Otros:**




## CONFIGURACIÓN DEL SISTEMA

**Clase de servicio:** 


**Horarios:**


**Funciones:**
*  **15-07** Funciones para las teclas de acuerdo al número de teclas de cada equipo.
*  **15-01** User Basic Setup
                   funcion:       marcación:
*  **15-07-06** 01 DSS/One Touch **9**24120000

**Extensiones:**
*  **Extensiones virtuales:** 50
     *  **11-04** Extensiones virtuales
          Las configuraciones se realizan de forma similar a las extensiones físicas.
*  **Extensiones físicas:** 128

*  **Extensiones móbiles:**
*  **15-22 Extensiones móbiles:**
      Mobile extensión setup.
      Elegir la extensión predefinida como móbile en la 11-02.
      
      Deben de ser números que no se esten usando dentro de las extensiones físicas.
      Una extensión móbile no debe registrarse cerca de una extensión fisica.
      ejemplo: última extension fisica= 20        Extensión móbile= 35
      
*  **15-22-01** Definir la casilla.
     Se puede definir casillas entre 0-999 pero se usa de la 900 en adelante.
     Mobile extension target setup.

*  **11-02** Se crean las extensiones y puertos que no están en uso.
     Se define el puerto y la extensión correspondiente a dicho puerto.
     
*  **15-22-02**     

     
     
     



**Restricciones:**
*  **21-04** Restriccion de extensiones y que clase va a usar. (1-5).
*  **21-05** Restricion de clases.
*  **21-05-01** Habilitado de acuerdo al código que marca.
             Hay que ir a verificar las restricciones de las marcaciones al 21-06-01
*  **21-05-08** Restriccion de los codigos de tablas 1,2,3.
*  **21-05-08** Números internacionales para no llamar.
     *  **tabla 1** Internacionales
     *  **tabla 2** Nacionales
     *  **tabla 3** 
*  **21-06-07** Los números a los que se le restringe llamada de acuerdo a la tabla número 1 `--*1*--`
*  **15-01** User Basic Setup
*  **15-01-03** Habilita la extensión para enviar registros a Teletax SMDR PrintOut
*  **15-01-04** Debe estar habilitado calling party number.
*  **15-02** Lenguaje y tono de llamada.



   

**Otros:**


