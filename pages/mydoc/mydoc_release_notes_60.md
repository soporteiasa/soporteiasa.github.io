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

**Horarios:**
*  **10-01** Comando para configurar hora y fecha
*  **10-01-09** Zona horaria

**Números (físicos/IP):**
*  **11-01** Configurar la longitud de digitos de extension (apartado de númeración) &nbsp;
             Configurar el número de la extensión.
*  **22-11** Asignar un número a las extensiones.

*  **22-11-01** Configuración para que la planta analice los últimos 4 dígitos.

*  **22-11-02** A qué extension se va asignar el número.
             
## CONFIGURACIÓN DE VIRTUALES Y MÓBILES.
**Extensiones virtuales:**
* **11-04** Extensiones virutales.
    Se configuran de forma similar a las extensiones físicas.

**Extensiones móbiles:**
* **15-22** Móbile extensión setup.
    La extensiones móbiles deben de ser números que no se estén usando entre las extensiones físicas.
    Elegir la extensión predefinida como móbile en 11-02. 

* **15-22-01** Definir la casilla desde 0-999 pero se usa de la 900 en adelante.
    Móbile extensón target setup.
    
* **15-22-02** Para que no pida confirmación DTMF para no darle contestar 2 veces.

* **15-22-03** Use normal trunk access code 

* **11-09-01** code QR

* **11-02** Se crean los puertos y extensiones que no están en uso.
    Una extensión móbile no se debe registrar cerca de una extensión física. (ext. física 900, ext. móbile 915).


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
**20-06:** ` 1 `.
**20-07:** Clase de servicio (Administrator level).
**20-07:**


**Horarios:**
