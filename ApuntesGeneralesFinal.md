# TAREAS DATASET
1. Conseguir ampliar el dataset (de LinkedIn): 
    1. Scrapear nuevas compañías.
    2. Añadir industrias (ahora hacerlo por scrapping).
    3. Contrastar número de empleados con el datasetSupercias
        1. Nos quedamos con el mayor.
    4. Limpiarlo.

# TAREAS DE CLUSTERING
1. Decidir categorías para los skills (e.g. the big five).
    1. Consideraciones:
    2. Hay mas info de la que no es B5.
    3. B5 tiene métricas asociadas.
2. Enteder y decidir como implementar TFIDF para crear clusters  (es una alternativa a la normalización)
    1. Aplicarlo al dataset preliminar.
3. Hacer ambos análisis y dicutir en conjunto la caracterización de los clusters (qué representa cada cluster)
    1. Agrupar skills en el dataset por la categoria elegida.
    2. Aplicar TFIDF (word ebbedings)
    3. 2 análisis de clusterins.
4. Nota: Primero clustering, luego sacas lo del ROA l... PRIMERO CLUSTERING (no incluyes el ROA)

# TAREAS DE GRAFO (EL GRAFO ES BIPARTITO)
1. Hacer el grafo (skills (puntuales) --> industria)
    1. Definir análisis.

# TAREAS DE CORRECCIÓN
1. Limpiar el cochino repositorio.
2. Arreglar la diapositiva 
3. Limpiar que no tienen sentido (ver capturas de las primeras diapos para el overview y datasets diapos)
4. Rediseño del overview y primar business question, hay caputars y una de las diapos tienes las conclusiones
   tentativas.
5. Barplot en lugar de listas
6. REvisar diapo de no detenerse (ese el comment)
7. Nada de fundos negros.

# PUNTOS 
1. Una de tus conclusiones es que el dataset de la supercias tiene inconsistencias "un dataset publico como es
   el de la Supercias puede tener inconsistencia", "Es posible detectar inconsistencias entre el rosado y su
   página de linked in y numero de empleados (hemos encontrado x inconsistencias mas)")
2. Dividir la presentación en 2:
    1. Comenzar haciendo el overview y preguntas relacionadas las 75k y pasado un punto decir que nos vamos
       ahora a enfocar en las copañías grades (high performers).


# FINAL OUTCOMES
1. Perfiles de movilidad
    1. Clustering, 2 análisis:
        1. Skills más importantes por ROA (aqui no van a entrar los bancos).
        2. Skills más importantes por industria.
    2. Aplica:
        1. TF-IDF
        2. Posiblemente una agrupación de skills.
    3. Ideas:
        1. Definir con referencias categorías de skills:
            1. Cognitivas.
            2. Socioemocional.
            3. Técnicas.
        2. The Big five?:
            1. Tiene 5 categorías
            2. Hay una métrica que deriva de esto.
        3. Habilidades del siglo 21
        4. Mantener igual una idea de saber cuales son las habilidades puntuales que más salen en categoría
           Big Five.
2. Grafo bi-partito (Social network) de:
    1. Skills --> industria
        1. Habilidades puntuales.

2. Readaptar la primera pregunta (Continuidad)




[Referencia para visualizaciones]: https://www.darkhorseanalytics.com/
