# Entrega 1

## Documentación de dominios y sub-dominios

### El alumno identificó y documentó correctamente todos los dominios y sub-dominios usando el DSL de ContextMapper [10pt]

SaludTech de los Alpes (STA) es una compañía
colombiana constituida en 2021 que se desenvuelve
en la industria del Vertical AI. 

Su enfoque principal es recaudar, procesar y distribuir imágenes médicas y diagnósticos anonimizados a compañías de IA y desarrolladores. Dichas imágenes y metadatos sirven como fuente de entrenamiento para modelos de IA. 

Lo primero a identificar son los dominios de negocio.

Pensando ampliamente podemos pensar en dos dominios que son:

**(a) Recaudar imagenes:** Es la posibilidad de que los proveedores de salud pueden proveer datos anonimizados a STA y obtener un pago por ello. En este caso lo que se propone es un pago acuerdo al nivel de uso de los datos. 

**(b) procesar imágenes médicas y diagnósticos anonimizados:** STA cuenta con 3 diferentes productos diseñados para servir como datos de entrenamiento de modelos de IA. 

**(c) distribuir imagenes médicas y diagnósticos anonimizados:**  Este posible dominio se centra en la distribución completa de las imagenes a los socios asociados. 

De todas maneras se puede ver una relación muy directa con (b) y (c) donde la distribución al hacerse a traves de los productos diseñados de STA que se encargan de el procesamiento de datos se sienten integrados y de cierta forma bien acoplados. Es así que se toma la decisión de fusionarlos en un dominio nuevo **(bc) procesar y distribuir imágenes médicas y diagnósticos anonimizados:** 

Para constituir cada uno de los dominios se tiene que poner en consideración sus distintos subdominios

**Para (a) Recaudar imagenes:**
  * Gestión de Proveedores de Salud
  * Recolección de Imágenes Médicas
  * Anonimización de Datos

**Para (bc) procesar y distribuir imágenes médicas y diagnósticos anonimizados:** 
  * Canonización de Imágenes
  * Procesamiento de Imágenes para IA
  * Presentación de Datos y Diagnósticos
  * Distribución de Imágenes y Diagnósticos