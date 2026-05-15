#Análisis de percepción social: inmigración en españa (CIS, 2017)

Este proyecto es un resumen de un informe realizado en la asignatura de Análisis de datos II en la carrera de sociología en la Universidad de Alicante. 

Este informe recogía datos sobre la percepción de los españoles ante los inmigrantes, usando el estudio 3190 del Barómetro del CIS. En este se aplicó SPSS con técnicas como Anova de un factor o Análisis factorial.

Sin enmabrgo, he decidido darle una vuelta e intentar usar en vez de SPSS, usar Python para la limpieza de datos empleando Pandas para la limpieza de datos y la transformación de estos mediante el proceso ETL. Y para poder visualizarlos mejor, en lugar de usar matplotlib, he usado Power BI para la visualización de estas variables. 

Para este dashboard, he seleccionado y transformado las variables del estudio 3190 del CIS  para poder centrar el analisis entre el perfil sociodemográfico y el prejuicio percibido. 

Las variables independientes son las siguientes: 
- Nivel de estudios: variable usada para medir el capital cultural, la cual se analiza desde estudios primarios hasta doctorado para observar cómo la formación influye en la apertura hacia la alteridad.
- Edad: nos permite un análisis de cohortes para identificar si existen diferencias generacionales en la tolerancia social.
- Sexo: variable de control para identificar posibles brechas de género en las opiniones actitudinales.

Las variables dependientes son las siguientes: 
- Competencia laboral: prejuicio económico, indicador clave de conflicto social en entornos laborales.
- Distancia social (matrimonio): basado en la escala de Borgadus, mide el grado de aceprtación de un inmigrante en la esfera íntima (racismo sutil).
- Valoración general: resume la actitud global del encuestado hacia el fenómeno migratorio.

A diferencia de lo que hice con SPSS, esta vez he limpiado y quitado los valores nulos con Python, recodificado escalas numericas a categorias legibles y filtrado NS, NC dentro de power BI para no saturar las graficas de información. Además, el dashboard nos muestra hallazgos interactivos diferenciados en categorias elegibles entre sexo y grupo de edad. Tras seleccionar lo que necesites, se te va a mostrar en gráficos los datos que te interesa conocer. 

Este dashboard no solo permite describir la muestra, sino entender que factores determinantes son los que tienen el papel más activo en la discriminación hacia los inmigrantes, transformando datos complejos en unidades de análisis medibles.
