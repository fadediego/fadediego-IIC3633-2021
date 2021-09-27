# Deep Learning based Recommender System: A Survey and New Perspectives

La lectura de la semana consistió en la primera mitad (págs. 1-17) del *paper* "*Deep Learning based Recommender System: A Survey and New Perspectives*" (Julio 2018), de S.Zhang et al. En términos generales,
el texto consiste en una revisión de los principales avances relacionados al *Deep Learning* en el área de los Sistemas Recomendadores, y las distintas arquitecturas utilizadas.
Para escribir el *paper* se revisaron más de un centenar de textos, lo cual sugiere *a priori* que se trata de un trabajo bastante exhaustivo.

En términos de contenido descriptivo, es poco lo que se puede criticar, dado que los autores recopilan información expuesta en otros trabajos. Sin embargo, los autores
también proponen un nuevo sistema de categorización de modelos de recomendación que utilizan *Deep Learning*. Lo propuesto corresponde a separar los modelos en dos
categorías: (1) Recomendación con bloques de redes neuronales, y (2) Recomendación con modelos híbridos profundos. Esta taxonomía de modelos de recomendación llama la atención,
puesto que la segunda categoría corresponde a combinaciones de casos particulares de la primera (los modelos híbridos profundos son mezclas de modelos de bloques neuronales).
Así, da la impresión que los autores simplemente propusieron una categoría que comprende todas las arquitecturas comunes, y otra que las mezcla, sin abordar necesariamente los
distintos comportamientos que puede significar cada una de las mezclas de modelos (p.ej. una mezcla de redes CNN y RNN puede tener un comportamiento notoriamente distinto que
un sistema híbrido de redes AutoEncoder y Adversarial). Viéndolo desde un punto de vista práctico, es posible que continuar con las clasificación común de modelos de recomendación
(filtrado colaborativo, basado en contenido, o híbrido) no hubiera significado un gran cambio al objetivo del *paper* (exponer una revisión de los principales modelos de recomendación
de tipo *Deep Learning*).

Otro aspecto notable del texto es que no incluye arquitecturas de tipo Transformer en el análisis, las cuales podrían haber estado incluidas en la subcategoría referente a
modelos de atención (*Attentional Models*). Una posible explicación de lo anterior, es que los modelos de Transformers no estaban siendo utilizados para Sistemas Recomendadores
al momento de la publicación del *paper* leído. Otra posible explicación, es que para aquel entonces dicho modelos no alcanzaban un desempeño aceptable en recomendación, por
lo que los autores no decidieron incluirlos. Sea cual sea el caso, los modelos de tipo Transformers fueron expuestos por primera vez en el *paper* "*Attention Is All You Need*" 
(véase [1]), publicado el año anterior a la fecha de publicación del *paper* leído durante esta semana, por lo que ya existían en tal momento. Es importante mencionar que
actualmente sí se han utilizado modelos de tipo Transformer para realizar recomendaciones (véase, por ejemplo, el *paper* [2], que tiene una implementación sobre MovieLens
disponible en [3]).

En conclusión, el *paper* "*Deep Learning based Recommender System: A Survey and New Perspectives*" presenta una recopilación de los principales modelos de recomendación de
tipo *Deep Learning*. Un aspecto del texto del cual su utilidad queda en duda es el sistema de clasificación de modelos de *Deep Learning* propuesto, el cual es simplemente
una separación entre modelos "puros" e híbridos. Por otro lado, se extrañó la inclusión de Transformers al texto, lo cual se pudo deber tanto a razones temporales, como a
razones de desempeño.

Referencias:
- [1] *Attention Is All You Need*, Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, Illia Polosukhin (2017). Recuperado de: https://arxiv.org/abs/1706.03762
- [2] *Behavior Sequence Transformer for E-commerce Recommendation in Alibaba*, Qiwei Chen, Huan Zhao, Wei Li, Pipei Huang, Wenwu Ou (2019). Recuperado de: https://arxiv.org/abs/1905.06874
- [3] *A Transformer-based recommendation system*, Khalid Salama (2020). Recuperado de: https://keras.io/examples/structured_data/movielens_recommendations_transformers/.
