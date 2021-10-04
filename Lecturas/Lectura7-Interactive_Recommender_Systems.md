# Interactive Recommender Systems: A survey of the state of the art and future research challenges and opportunities
La lectura de esta semana fue "*Interactive Recommender Systems: A survey of the state of the art and future research
challenges and opportunities*" (2016) de los autores Chen He, Denis Parra y Katrien Verbert. En términos generales, el texto
consiste en la propuesta de una interfaz general para describir sistemas de recomendación interactivos, y la revisión de múltiples
ejemplos concretos de éstos. En los próximos párrafos, se expondrán algunos aspectos que vale la pena mencionar, tanto del trabajo
leído, como del área de Sistemas Recomendadores Interactivos.

En primer lugar, en el *paper* se muestran sistemas recomendadores interactivos cuyo fin es atacar alguno o varios de los problemas
relacionados a la transparencia, justificación y diversidad de las recomendaciones, el *cold-start* (que dificulta la recomendación
a usuarios nuevas), la controbilidad de los sistemas y su impacto en las recomendaciones, y la incorporación de contexto (como
emociones) a los sistemas. Si bien en el *paper* se mencionan los impactos que tuvieron las distintas técnicas visuales y objetivos
con respecto a la relación usuario-sistema, sería interesante ahondar en los efectos producidos sobre la compañía que aplica dichos
sistemas. Por ejemplo, tal como se vio en [1], una métrica de evaluación de sistemas recomendadores es el ingreso que le genera a la
empresa. Ponerle números a la variación del ingreso, ante la presencia/ausencia de sistemas recomendadores interactivos (más
específicamente, las visualizaciones), podría ser un aspecto relevante a considerar en el futuro. La estandarización de las
distintas técnicas, dependiendo de cuál es el objetivo que se busca, podría llevar a una estrategia de mercado que dependa
de cada visualización de forma diferente. En el texto se menciona que aún no existe una estandarización adecuada de sistemas
recomendadores interactivos, por lo que aún hay espacio para investigar en dicha dirección.

Por otra parte, un aspecto que seguro llamó la atención tanto a los autores del texto, como a mí cuando leía el *paper*, era la
ausencia de sistemas interactivos cuyo objetivo fuera mostrar recomendaciones que cayeran en las categorías de *novelty* (novedad)
y *serendipity* (casualidad). Algunos estudios al respecto han sido publicados posterior a la fecha de publicación de la revisión,
tales como [2]. Dicho estudio consistió en evaluar el efecto de distintos tipos de visualizaciones sobre la capacidad de mostrar
adecuadamente la exactitud (*accuracy*) y la casualidad (*serendipity*) de las recomendaciones. Si bien la investigación se llevó
a cabo por medio de un cuestionario de tan solo 60 participantes en un ambiente cerrado (el Instituto de Ciencias Administrativas
de Peshawar, Pakistán), corresponde a un buen punto de partida para analizar la relación entre la casualidad y los sistemas
recomendadores interactivos.

De seguro que existen muchísimos aspectos relevantes sobre los cuales se podría ahondar en el área de Sistemas Recomendadores
Interactivos, y que fueron mencionados en esta crítica. Sin embargo, como se mencionó en los párrafos anteriores, un buen punto
de partida podría ser el análisis del impacto de sistemas recomendadores interactivos en el negocio de cada empresa, y desarrollar
aún más el análisis de la representación visual de recomendaciones casuales.

Fuentes:
- [1] Guy, S., & Gunawardana, A.. (2011) “Evaluating recommendation systems.” In Recommender systems handbook, pp. 257-297. Springer US, 2011. pdf
- [2] Ahmad Hassan Afridi (2018). Visualizing Serendipitous Recommendations in User Controlled Recommender System for Learning
