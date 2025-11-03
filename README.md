# Práctica Profesional - Censo 2022

Repositorio del trabajo realizado en el marco de la **Práctica Profesional Supervisada** en la **Dirección General de Estadística** de la Municipalidad de Rosario.  




## 📂 Datos

Este repositorio combina información censal y geográfica de la ciudad de Rosario.

| Fuente | Descripción | Ubicación | Observaciones |
|:-------|:-------------|:------------------|:---------------|
| **Censo Nacional 2022 (Redatam - INDEC)** | Datos censales desagregados por radio censal para la ciudad de Rosario. Incluye variables demográficas, de hogar y vivienda. | `data/raw/datos_censales_redatam.csv` | Extraído del [portal Redatam (INDEC)](https://redatam.indec.gob.ar/binarg/RpWebEngine.exe/Portal?BASE=CPV2022&lang=ESP).|
| **Base cartográfica de radios censales 2022** | Polígonos geográficos de los radios censales del Censo Nacional 2022 de Argentina, útil para georreferenciar datos del censo  y análisis espaciales | `data/external/radios/` | No incluida en el repositorio por su tamaño. Ver instrucciones de descarga debajo. (1)|
|...|

(1) **Base cartográfica de radios censales:**  
**Fuente:**  
Rodriguez, Gonzalo Martin (2024).  
*Base cartográfica de radios del censo argentino 2022: Primera versión revisada y corregida para uso en Sistemas de Información Geográfica.*  
Consejo Nacional de Investigaciones Científicas y Técnicas (CONICET).  
[http://hdl.handle.net/11336/238198](http://hdl.handle.net/11336/238198)
**Instrucciones**:
Descargar el archivo `RADIOS_2022_v1_0.rar` desde el enlace anterior, descomprimirlo, y colocar **todo su contenido** directamente dentro de esta carpeta (`data/external/radios/`).




