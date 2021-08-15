# RECURSOS GENERALES:
[Word]: https://espolec-my.sharepoint.com/:w:/g/personal/axvargas_espol_edu_ec/Eezkxmm7hPRGmRHDLGC9dvMB5Y5RaXtkt2ECGapEMbHMHw?e=D82BFO
[PowerPoint]: https://espolec-my.sharepoint.com/:p:/g/personal/jfnebel_espol_edu_ec/EaSfWstvKRpEviCReakfGB4BDJ6fsptMKnaP2RKhSP36Ww?e=yz89kj
[Repo]: https://github.com/JFNebel/ecuadorian-graduates-workforce-mobility 
[Project requirements]: ../Ciencia_Datos/Proyecto/SegundoParcial/PROYECTO-REQUERIMIENTOS-FINAL.pdf

<! =========================== ENTREGA =================================>
# GENERAL
1. <Industria> == categorias hechas apartir de <col_actividad_económica>

# PROBLEMAS GENERALES ENCONTRADOS
1. Se debe generar categorías para grupos de <actividad_económica>
2. La doctora quiere ver un vector en el que clusters de skills y categorías de <actividad_económica>
   (<industria>).

# NECESITAMOS DF Y NOTEBOOKS
1. Eliminar empresas con 0 ingresos/ventas:
    1. Esto implica volver a correr los análisis y actualizar documentos para todos los miembros.
2. Sección del overview que tenga análisis de variables numéricas.
3. Un análisis de outliers (se me ocurre con utilidad generada, uno positivo y otro negativo).
4. Hacer algo con los ingresos y cantidad de empleados.
5. Ver como chequear que tenemos ya los empleados al menos con sentido de cada empresa (no solo para el rosado)
6. <Técnicas de clustering>
7. <Social network analisis>
    1. Hacer un grafo
    2. Necesita sectores (para hacer grafos po sectores)
8. Visualizaciones:
    1. Etiquetar ejes y tener un título en todo
    2. Visualizaciones temporales
    3. Personalizar ticks
    4. Side by side

# NECESITAMOS PP
1. Sección overview:
    1. Falta ponerlo como tal (hacer la sección en sí)
    2. Falta un análisis de variables numéricas (no solo categóricas)
2. Falta actualizar lo de datasets
3. Actualizacion de hallazgos (los tres tenermos que)
6. Opcional: Empezar a poner el PP en un formato como el del pdf

# NECESITAMOS WORD
1. Similar al PP
4. Opcional: Empezar a poner el word en un formato como el del pdf

[Juan]: 
1. Responsable de preguntas 1 y 5.
2. Grupo <industria>
3. Limpieza de empresas sin ventas/ingresos y chequear numero de trabajadores.
    1. poner lo de correlacion (scatterplot, ver pregunta 5).
4. Overview numérico
    1. Hacer su propio notebook.
5. Análisis de outliers.
    1. Negativo y positivo.
6. Usar Spearman para la pregunta 5.
7. Arreglar el statement de la cantidad de empleados y su porcetaje (ver el sidweb)
8. Mejorar sección de datasets (pp)
9. Label y titular todos mis graficos.
10. Actualizar hallazgos en PP y Word (ventas 0)

[Danny]: 
1. Responsable de preguntas 3 y 6.
    1. Terminar esas preguntas.
2. Se cumple por pregunta 3: Clusters de skills (por ejemplo: técnicas, lenguajes, humanas etc.)
    2. Se debe saber a qué corresponde cada cluster (no pueden ser solo: cluster#1, cluster#2, etc.)
    3. No olvidar que se quiere normalizar y ver que pasa si no se normaliza (pdf de entrega)
3. Ayudar a Andrés con la pregunta de grafos (pregunta 4).
4. Label y titular todos mis graficos.
5. Actualizar hallazgos en PP y Word (ventas 0) de todo lo realizado. 

[Andrés]: 
1. Grupos <industria>
2. Revisar que la cantidad de empleados de las campañías tenga sentido (puede pasar como pasó con el Rosado).
3. Responsable de pregruntas 2 y 4 (grafo)
    1. Hacer esas dos preguntas.
4. Label y titular todos mis graficos 
5. Actualizar hallazgos en PP y Word (ventas 0) de todo lo realizado.


## COSAS QUE SE NOS HA PEDIDO PARA LA PRÓXIMA ENTREGA
1. Incluir más empresas en nuestro main dataframe.
    1. Que las empresas sean también más variadas aún si no pertenecen al top 100 (e.g: Banco Bolivariano)
    2. Sería óptimo preguntar a la dra. cuales quisiera ver ella.

<! ===================================================================>






<! ============================== WS =================================>
1. Correlación: revisar el factor de corerlación mejor usar sperman por defecto pandas usa person y es solo
   para distribuciones normales, viabilidad de la correlación verificar que se espera responder, SUGERENCIA:
   realizar un cluster de la actividad de las empresas y segun eso determinar habilidades por ejemplo sector
   de elecomunicaciones(ingles, servicio al cliente....)

2. choroplet: se puede realizar de un choroplet para eviar sobreponer información o saturar el gráfico
   SUGERENCIA: en lugar de mapear las empresas y las universidades segmentar las empresas por tipo similar al
   item anterior y ver de que lugares vienen los empleados(ejemplo sector farmaceutico---> predomina la
   universidad X,Y,..)

3. Para el caso de habilidades de empleados, asi como actividades que realizan SUGERENCIA: utilizar lo visto
   en la última clase ls factores IDF de esta forma tomar en dataframe las empresas como documentos(Compara
   las habilidades mas representativas en todas las empresas son transversales por lo tanto son menos
   importatntes) se puede usar variantes y clusters

4. SUGERENCIA: distribucion por tipo de empresa(ejemplo Minera, Farmaceutica,..) y determinar -frecuencia
   carreras por tipo de compañia  con eso analizar la competitividad de de un perfil de universidad.

5. Clustering diferentes grupos que tienen en comun, SUGERENCIA:analizar los factores comunes entre las
   empresas ejemplo(utilidad, ) evitar localización o establecer un buen criterio de análisis.

6. Sobre el sesgo de contratación por region, lareadidad ecuatoriana de movilidad laboral pude indicar que las
   personas no les gusta movilizarse por razones de trabajo lo cual no significa que las empresas no quieran
   contratar personas de otras localidades sino que estas personas no postulan a estos trabajos, reforzar el
   análisis o plantear una pregunta que sea mejor estructurada.

7. la presentacion debe llevar una respuesta a las preguntas de negocio tomar en cuenta que es una
   presentación para personas que tienen un criterio tecnico-medio por lo que se debe incluir metricas y
   posibles algoritmos, métodos o herramientas que aydaron a resolver, incluir una explicacion de todos los
   dataset en nuestro caso los 7..
