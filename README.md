# Práctica Profesional - Censo 2022

Repositorio del trabajo realizado en el marco de la **Práctica Profesional Supervisada** en la **Dirección General de Estadística** de la Municipalidad de Rosario.  


![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=for-the-badge&logo=geopandas&logoColor=white)
![Metabase](https://img.shields.io/badge/Metabase-509EE3?style=for-the-badge&logo=metabase&logoColor=white)

## 🎯 Resumen del trabajo
Análisis de datos censales (2022) para evaluar y corregir indicadores de pobreza en la ciudad. El proyecto expone las limitaciones del indicador tradicional de **Necesidades Básicas Insatisfechas (NBI)**, analiza el **Índice de Privación Material de los Hogares (IPMH)**, desarrolla una comparativa con el **ReNaBaP** y culmina con un tablero interactivo en Metabase para facilitar la exploración de los indicadores censales estudiados en la ciudad de Rosario.

## 📂 Contenido
* 📄 **[Informe Completo (PDF)](./Informe%20PPS%20-%20Torres%20Santiago.pdf):** Documento detallado de la Práctica Profesional Supervisada.
* 📊 **[Vistas del Dashboard](./dashboards/):** Capturas del tablero desarrollado en Metabase.
* 💻 **[Notebooks](./notebooks/):** Código fuente en Python con el ETL, EDA, cruces espaciales y análisis realizados. 

## 💡 Hallazgos clave
* **El subregistro del NBI:** Se demostró que el indicador subestima gravemente el déficit habitacional (1,64%). Al corregir el sesgo e incorporar tipologías precarias omitidas (como "Casas Tipo B" y "Ranchos"), el déficit real escala al **9,69%**.
* **El "punto ciego" del centro:** Mediante la aplicación del IPMH, se reveló que la zona céntrica sufre una fuerte privación de ingresos concentrada en hogares unipersonales, una vulnerabilidad económica que el NBI tradicional no contempla.
* **Validación territorial:** Se desarrolló una métrica de intersección espacial para cruzar los datos censales con los polígonos oficiales del **ReNaBaP**. Se obtuvo una alta correlación (**r = 0,72**), validando estadísticamente que los indicadores calculados reflejan la realidad del territorio.

## 🗄️ Para reproducir localmente el proyecto
Las bases de datos y capas GIS no están incluidas en el repositorio. Para acceder a los mismos debe:
1. Descargar el archivo `datos_PPS_censo.zip` desde **[este enlace de Google Drive](https://drive.google.com/file/d/1rVSzGVCFHb5g_l7ip6Ff5Qw11B5KDmUF/view?usp=sharing)**.
2. Descomprimir el archivo y colocar la carpeta `data/` en la raíz del proyecto.
3. Ejecutar los Jupyter Notebooks de la carpeta `notebooks/`.

---
Santiago Torres  
**Contacto:** [LinkedIn](https://www.linkedin.com/in/santiago-m-torres/) | Correo: santiago.torres@ingenieria.uner.edu.ar
