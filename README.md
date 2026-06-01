# Int1-Practica02-250900"
---
En esta practica aprenderemos a utilizar la sherramientas Git y Github para el control de versiones de proyecto de desarrollo de software, aplicando principios de buena practica
en documentos , desarrollo colaborativo y respaldo en la nube del proyecto integrador

Elaborado por: **Jeovany Cantellano Vargas**\

Materia: **Proyecto Integrador**\

Docente: **M.T.Z. Marcco Antonio Ramirez Hernandez**\

Periodo: **Marzo - Agosto 2026*  \

---

## comando basicos para maqutado de la documentacion utilizando el estandar de Markdown (.md)

---

Markdown es el estandar utilizando Git Github para estilizar (maquetar) la documentacion de proyecto entender el contexto y operacion del mismo

### 1. Encabezados o titulos (HEADERS)

Para poder realiza una buena documentacion del proyecto debemos distribuir correctamente los contenidos para poder delimitar o hacer enfasis (enfatizar) es decir resaltar las secciones mas importantes, podemos utilizar lo siguiente:

**EJEMPLO**

# Encabezado de nivel 1
## encabezado de nivel 2
### encabezado de nivel 3
#### encabezado de nivel 4
##### encabezado de nivel 5
###### encabezado de nivel 6
####### encabezado de nivel 7 -  *El estandar solo permite 6 niveles para titulos, a partir del septimo seran presentado como texto plano (sin estilo)*

### 2. separadores (SEPATORS) 

Si se desea marcar una separacion visual de los contenidos podemos utilizar una linea horizontal indicando tres caracteres - continuos, en el maquetado 

**EJEMPLO**

### Titulo de la seccion
---
parrafo 1: este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 este texto es del parrafo 1 

parrafo 2:este texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2  texto es del parrafo 2 este texto es del parrafo 2, el estandar de markdown distingue los parrafos 

en caso de quue necesitemos alinear el parrafo a **izquierda**, **derecha**, **central** o **justificar** deberemos utilizar una etiqueta <p> con la propiedad align y direccion deseada

<p align="left"> parrafo alineado parrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineadoparrafo alineado
<p align="center"> parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro parrafo alineado al centro 

<p align="right"> parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha parrafo alineado a la derecha 

<p align="justify"> parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado parrafo justificado

### 4. Enfatizado de texto

texto en negritas : para resaltar texto importante que no se aun texto porque esto inicialmente debems encerrar el texto desdeando entre doble asteriscos simples (**)

ejemplo: este texto esta en **Negritas**

texto en cursiva (Italico): para hacer referencia a texto utilizando el formatp inclinado o italico basado con encerarr el texto deseadpo entre dos asteriscos simple (*)

ejemplo: este *texto* esta *inclinado*

texto en cursiva y negritas: para logar esta estilizacion en el documentacion basata con juntar ambas configuracion, es decir encerramos el texto en triple asteriscos (***)

ejemplo ***ste texto esta en negritas e italico***

texto techado: en algunas ocaciones es necesario dar formato al texto con un efecto de como es incorrecto generalmente esta idea se transmite por que el texto  techado es decir con unalinea que lo marca por la mitad

ejemplo: se dice haya no (~~ahiga~~)

texto subrayado: en este tipo de formato el texto queda sobre una linea inferior para denotar su relevancia este formato no tiene una version rapida en el estandar de MARKDOWN pero dada su similiaridad a HTML podemos utilizar las etiquetas ''' <u> ''' y '''</u>.

ejemplo: el <u>texto</u> debe estar <u>subrayado</u>

tetxo en super Indice: en algunas ocaciones se reuqiere dar formato a formulas estadisticas que requiere potencias entre otras aplicaciones podemos utilizar el tag de HTML ``` <supe> 
tetxo en super Indice: en algunas ocaciones se reuqiere dar formato a formulas estadisticas que requiere potencias entre otras aplicaciones podemos utilizar el tag de HTML ``` <supe> ``` y ``` </sup> ``` para determinar el formato 

ejemplo : para elevar x al cuadrado tendriamos lo siguente x<sup>2</sup>

texto en subindice: en el caso de qimica se utilizan subindices para representar formulas para ellos podemos utilizar el formato de texto con la etiqueta HTML

Ejempo: la formula del agua es H<sup>2</sup>O.

### 5 listas 

cuando realizamos documentacion utilizamos el estandar de MACKDOWN es comun que tengamos que en listar elementos requerimos de hardware requerimos de software o enumerar pasos de como el software debe ser instalado paso a paso or eso debemos saber como creamos listas de cuales hay de 3 tipos: **ordenamos (numeros)** , **desordenados (viñetas)**, y **mixtas (viñetas y numeros)**

1. listas ordenadas

esta dberemos estar enumerados con un numero seguido por un punto y un espacio en clanco para comenzar con el listado

1. Pc
2. Wifi
3. Modem
4. Smartphone
6. Smart Tv
5. tablet 

2. estas listan no llevan un numero, su no un aviñeta(simbolo), y suele listar elemtos que no requerimos un orden especifico

- pan
- leche
- huevo
- azucar

3. lista mixta
 son aquellas que mezcla ambos elementos
 - 3° A DSM
 1. Juan
 2. pedro
 3. alejandro
 - 3° DSM
 1. romina
 2. daniel
 -3° C DSM
 1. yahir
 2. liseth
 3. jeovany
 4. erick

 ### 6. bloques de codigo (CODE BLOCKS) o citas (BLOCK QUOTES)

Estos codigos de texto se utilizan para llamar la atencion del lector en pasos que son importantes realizar alguna reseña o segmentar lineas de codigo que deberan integrar en una terminal de comandos o lineas de ejercicio

-cuadro de citas (block quotes)
son cajas estilizadas en colores grises por defecto con un argen claro

ejemplo:

para enlistar las carpeta sy archivos desde una terminal de comandos en el sistema operativo de window debemos usar el comando:

> C:dir

despues oprimimos la tecla "enter"

tambien podemos usar texto miltilinea

ejemplo:

> - descargar el archivo instalado desde la pagina oficial www.mysql.com
> - instalar el servidor de base de datos
> - definir el puerto y contraseña para el ususario **root**
> - inicializar el servidor de base de datos
> - conectarnos a la base de datos para verificar que se instalo correctamente

bloques de codigo

es comun que en la documentacion del proyectoo de software demos al ususario un par de instrucciones de como instalar configurar desplegar y testeae (pruebas) nuestro producto desarrolladopor tal motivo el estandar  marckdown nos permite enfatizar estas instrucciones simulano estar en la terminal de sistema operativo para delimitar este codigo basta encerrarlo un triple caracter de bacltic (acento o tilde inverso``` ' ```)


ejemplo:

para clonar el documento ingresa la siguente instruccion

```

C:\Users\PC-06\Desktop>git clone https://github.com/Jeovany-Vargas/Int1-Practica02-250900
Cloning into 'Int1-Practica02-250900'
```
a diferencia de los bloques de codigo de citas las topologias y significado asociado

### 7. tablas

en caso de que nesecitemos estructurar datos o informacion relevante para la documentacion podremos utilizar el formato de tablas para lo que tenemos considerar la estructura base de una tabla

- usa | para delimitar las columnas
-usa --- para separar las filas del encabezado

ejempo:

|titulo1|titulo2|titulo3|titulo4|
|---|---|---|---|
|Fila 1, celda 1|Fila 1|celda 2|fila 1|celda 3|fila 1|celda 4|
|Fila 2, celda 1|Fila 2|celda 2|fila 2|celda 3|fila 2|celda 4|
|Fila 3, celda 1|Fila 3|celda 2|fila 3|celda 3|fila 3|celda 4|

### 8. Hipervinculos (links)

parapoder hacer referencia a documentos internos o externos dentro del repositorio debemos respetar la siguiente estructura

```
[texto que el usuario  leera](url o donde te dirigira) "texto que aparecera cuando pongas el cursor dobre la liga"
```

ejemplo:
- Ligar externas
[Google](https://google.com)

- liga internas
[acerca del autor](./aboutme.md "conoceme mas")

