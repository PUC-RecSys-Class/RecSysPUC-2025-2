# IIC3633 Sistemas Recomendadores
Marzo-Julio 2025

### Equipo Docente e Información Administrativa
**Instructor**: [Denis Parra](http://dparra.sitios.ing.uc.cl), Profesor Asociado PUC Chile, Ph.D. University of Pittsburgh

**Ayudantes**:
* [Alejandro Plaza](#), Estudiante de Magíster, Ciencia de la Computación PUC Chile (aplaza2@uc.cl).
* [Daniel Sebastian](#), Estudiante de Magíster, Ciencia de la Computación PUC Chile (daniel.sebastian@uc.cl).
 
**Institución**: Pontificia Universidad Católica de Chile

**Horario cátedra**: Martes y Jueves, Módulo 3 (11:00 a 12:10). Salas TMP104 y NT202 respectivamente.\
**Horario ayudantía**: Lunes, Módulo 5, sala H1 (14:50 a 16:00).

**Sitio web lecturas**: [Perusall](https://app.perusall.com/join/parra-4xnh9)

**Programa** IIC3633, 1er Semestre 2025: [pdf](https://dparra.sitios.ing.uc.cl/pdfs/IIC3633Sist%20Recomendadores_v5.pdf).

### AVISOS

**Fechas de Seminarios (12/05)**:
- Se publicó el listado definitivo de [papers y grupos de seminario](https://uccl0-my.sharepoint.com/:x:/g/personal/dparras_uc_cl/EfyGP1fWSZtNiaN-MMAVe5oBsUlU5WtnYNzG5inT2dDxwA?e=183oxZ). Además, se publicó el archivo para inscribir la [fecha de presentación](https://uccl0-my.sharepoint.com/:x:/g/personal/dparras_uc_cl/ESvMv0yEcL1OiuPmfHbwIhABpoFv6BV_ntdshYcQdWCPfw?e=yg0C7h) del seminario, el cual tienen hasta el viernes 16 de mayo para inscribir.

**Papers de Seminarios (24/04)**:
- Se encuentra disponible el [Excel de inscripción de papers](https://uccl0-my.sharepoint.com/:x:/g/personal/dparras_uc_cl/EfunNfo_mEhArjucY4srQ_8BeTXdutC6Z_26eIhJvLjBug?e=9aSqWe), donde tienen hasta el jueves 8 de mayo hasta las 20:00 para inscribir un paper junto a su grupo.

**Proyecto de Curso (15/04)**:
- Se publicó el enunciado del [Proyecto de Curso](https://github.com/PUC-RecSys-Class/RecSysPUC-2025-1/blob/master/proyecto/Enunciado_Proyecto_Final_RecSys_2025_1.pdf), donde se pueden ver las fechas y requesitos de cada entrega.

**Cambio de Sala Oficializado** (31/03):
- El cambio de sala de la cátedra del curso ya es oficial y las nuevas salas se encuentran actualizadas tanto en el portal, en buscacursos y en este README. Tener cuidado con la sala, puesto que no es la misma los días martes y jueves.

**Sala Clases 25/03 y 27/03** (24/03):
- Como todavía no es oficial el cambio de sala, durante esta semana se continuará utilizando la sala K303 para las clases.

**Grupos Tarea 1** (24/03):
- Se publicó el listado de [grupos de trabajo](https://uccl0-my.sharepoint.com/:x:/g/personal/dparras_uc_cl/EQMYwiUukqhHkQncyoqFFygBrzHmjLCke9rhwskS9T3WxA?e=YY8ngc) para la Tarea 1.

**Tarea 1** (18/03):
- Se publicó el enunciado de la [Tarea 1](https://github.com/PUC-RecSys-Class/RecSysPUC-2025-1/blob/master/tareas/Tarea_1_RecSys_2025_1.pdf), con fecha de entrega el dia **viernes 11 de abril del 2025** a las **20:00**.

### Descripción del Curso

El curso de Sistemas Recomendadores cubre las principales tareas de recomendación, algoritmos, fuentes de datos y evaluación de estos sistemas. Al final de este curso serás capaz de decidir qué técnicas y fuentes de datos usar para implementar y evaluar sistemas recomendadores.

**Software**: [Suprise](http://surpriselib.com/), [Implicit](https://github.com/benfred/implicit) y [pyRecLab](https://github.com/gasevi/pyreclab/).

<!-- ## Planificación general (sujeta a actualización) -->

## Contenidos por Semana

**Coursera** <br/>
Los contenidos de las semanas 1, 2 y 4 los puedes revisar a tu ritmo en este curso de 4 módulos de Coursera llamado [Fundamentos de Sistemas de recomendación](https://www.coursera.org/learn/fundamentos-de-sistemas-recomendadores)

| Semana  | Tema             | link slide(s) | 
|:--------|:-----------------|:-------------:|
| 1       | **PPT Evaluaciones**                                          | [slides](https://uccl0-my.sharepoint.com/:p:/g/personal/dparras_uc_cl/Ecai9T_qNFhEgRdkanFN3K0BrEfq59CHT9JLkg4cSkAerQ?e=0IShzH)    | 
| 2       | **Ranking no personalizado y Filtrado colaborativo (FC)** | [slides](./clases/s1-c2-nonpers-UBCF.pdf)    | 
| 2       | User-based FC con clustering                          | [slides](./clases/s1-c2-UBCF_clustering.pdf)    | 
| 2       | Pendiente Uno                                         | [slides](./clases/s1-c2-SlopeOne.pdf)    | 
| 2       | **Item-based FC**                                         | [slides](./clases/s2_c1-IBCF.pdf)    | 
| 2       | **Factorización Matricial: FunkSVD**                      | [slides](./clases/s2_c2-Factorizacion_matricial.pdf) ([apunte FunkSVD](./clases/FunkSVD_2025_iic3633.pdf))   |
| 3       | **Implicit Feedback CF**                                  | [slides](./clases/s3_c1-Implicit-feedback.pdf)    |
| 3       | **Bayesian Personalized Ranking (BPR)**                   | [slides](./clases/s3_c2-BPR.pdf)    |
| 4       | **Evaluación: metricas de error y ranking**               | [slides](./clases/s4_c1-metricas_v2.pdf)    |    |   [slides P Castells LARS 2019](http://ir.ii.uam.es/castells/lars2019.pdf)                |
| 4       | **Evaluación II: Cobertura, diversidad, novedad**                        | [slides](./clases/s4_c1-metricas_v2.pdf)    | 
| 4       | **Evaluación III: Tests estadísticos**                        | [slides](./clases/s4_c2-tests_estadisticos.pdf)     |
| 4/5       | **Recomendación basada en contenido 1**                   | [slides](./clases/s5_c1-content-2024.pdf)    | 
| 5       | **Recomendación basada en contenido 2**                   | [slides](./clases/s5_c2-content-2024.pdf)    | 
| 5       | **Recomendación basada en contexto**                      | [slides](./clases/s6_c1-contexto.pdf)    |
| 5/6       | **Máquinas de Factorización**                             | [slides](./clases/s6_c2_p2-FMachines.pdf)    | 
| 6       | **Recomendación híbrida**                                 | [slides](./clases/s6_c1-hibridos.pdf)    | 
| 6       | **Recomendación por ensambles**                           | [slides](./clases/s6_c2_p3-blending_ensemble.pdf)    |
| 6       | **Deep Learning I: Intro**                             |  [slides](./clases/s6_c2_DeepL_CF.pdf)    | 
| 7       | Deep Learning II: Tres proyectos                             |  [slides](./clases/s7_c2_deep_learning_s.pdf)    |
| 7       | **Ideas de proyecto final (2024)**                            |  [slides](./clases/ideas_proyectos-2024-IIC3633.pdf)    |
| 8-9       |  Bandidos multibrazos                            | [slides](https://drive.google.com/file/d/1SlDt7UCDrtJBIPUxAMjhqzsjz6uelyIn/view?usp=sharing)    |
| 10       |  Aprendizaje Reforzado Intro | [slides](./clases/s10_c1_aprendizaje_reforzado.pdf)    |
| 10       |  Aprendizaje Reforzado for RecSys I| [slides](./clases/s10_SSRL_recsys_2021.pdf)    |
| 10       |  Aprendizaje Reforzado for RecSys II| [slides](./clases/s10_RecSys_RL_Slides_ICML_2024.pdf)    |
| 11       |  GNNs para SR | [slides](./clases/s11_c1_gnn_for_recsys.pdf) |
| 11      | Sistemas Justos, Explicables y Transparentes                              | [slides](./clases/s11_FAccT.pdf)    | 
| 12       | 10 problemas en Sistemas de Recomendación                                     |   [slides](./clases/s12_c2_10bigproblems-recsys-small.pdf)       | 

### Planficación 2025-I

<img width="1064" alt="Image" src="./clases/Planificacion IIC3633 2025-1.png" />

### Código de Honor

Este curso adscribe el Código de Honor establecido por la Escuela de Ingeniería el que es vinculante. Todo trabajo evaluado en este curso debe ser propio. En caso de que exista colaboración permitida con otros estudiantes, el trabajo deberá referenciar y atribuir correctamente dicha contribución a quien corresponda. Como estudiante es su deber conocer la versión en línea del Código de Honor.

**IMPORTANTE**: En este curso se permite el uso de modelos de lenguaje (ChatGPT, Gemini, Claude, etc) como apoyo en el desarrollo de las evaluaciones del curso, siempre y cuando no reemplaze el trabajo por parte de cada estudiante. En caso de usar alguna inteligencia artificial en el desarrollo de sus evaluaciones, se deberá citar dicho uso y compartir el enlace a la conversación (o conversaciones) con las IAs correspondientes en la entrega de la evaluación correspondiente.

### Evaluaciones

Detalles de las evaluaciones en [esta presentacion](https://uccl0-my.sharepoint.com/:p:/g/personal/dparras_uc_cl/EZ8G_FkyCKJAt6Fx23H7GWkBKl6ZeEdF9v222wJ5vAD5kA?e=9CvDt5)

**Prácticos (10%)** 

Habrá una actividad práctica relacionada a cada ayudantía, la cual consistirá en un desafío de código que deberá ser entregado por Canvas el viernes de la semana correspondiente a las 20:00. El promedio de los prácticos tendrá una ponderación del 10% en la nota final del curso.

**Tarea 1 (20%)**

Al final de las primeras 4 semanas, las(los) estudiantes implementarán mecanismos de recomendación para predecir ratings y para rankear items en un dataset que se entregará durante clases.

**Lecturas Semanales (5%)**

Cada alumno debe crear una cuenta en el sitio [Perusall](https://app.perusall.com) con su correo UC (codigo de curso **PARRA-4XNH9**). Cada semana deberá escribir 5 comentarios propios y 2 comentarios respondiendo a sus compañeros en los módulos de las lecturas marcadas como obligatorias.

Para descargar los archivos se sugiere buscarlos en [Scholar](https://scholar.google.cl) o a través de [EZProxy](https://login.pucdechile.idm.oclc.org/).

Fecha de revisión de comentarios de lecturas: El post de la semana x, tiene fecha de entrega el lunes a las 20:00 de la semana x+1. Ejemplo: Los comentarios de las lecturas de la semana 1 (clase el 6 de marzo) se entregan a más tardar el lunes 10 de marzo de 2025 a las 20:00.

**Seminario (25%)**

En la segunda mitad del semestre, los estudiantes formarán grupos para leer un artículo y realizar una presentación acerca de este frente al resto del curso. Se anunciarán las fechas y los artículos presentables de manera oportuna.

**Proyecto Final (40%)** 

Durante abril, las(los) estudiantes enviarán una idea de proyecto final, la cual desarrollarán durante mayo y junio. Enviarán un informe de avance a fines de octubre, para hacer una presentación de su proyecto al final del curso en una sesión de posters.

**IMPORTANTE**: Todas las entregas del curso son a las 20:00 del día de entrega correspondiente.

### Semana 1 (entrega el 10 de marzo):  

**Obligatorias**  
* Kluver, D., Ekstrand, M. D., & Konstan, J. A. (2018). Rating-based collaborative filtering: algorithms and evaluation. Social information access: Systems and technologies, 344-390.
[pdf](https://doi.org/10.1007/978-3-319-90092-6_10)
**secciones (1-6)**

**Sugeridas**
* Schafer, J. B., Frankowski, D., Herlocker, J., & Sen, S. (2007). Collaborative filtering recommender systems. In The adaptive web (pp. 291-324). Springer Berlin Heidelberg. [pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.130.4520&rep=rep1&type=pdf)
* Sarwar, B., Karypis, G., Konstan, J., & Riedl, J. (2001). Item-based collaborative filtering recommendation algorithms. In Proceedings of the 10th international conference on World Wide Web (pp. 285-295).
* [Post original FunkSVD](https://sifter.org/~simon/journal/20061211.html)  
* Lemire, D., & Maclachlan, A. (2005). Slope One Predictors for Online Rating-Based Collaborative Filtering. In SDM (Vol. 5, pp. 1-5).

### Semana 2 (entrega el 17 de marzo):

**Obligatorias**  

* Kluver, D., Ekstrand, M. D., & Konstan, J. A. (2018). Rating-based collaborative filtering: algorithms and evaluation. Social information access: Systems and technologies, 344-390.
[pdf](https://doi.org/10.1007/978-3-319-90092-6_10)
**secciones (7-9)**

**Sugeridas**  
* Hu, Y., Koren, Y., & Volinsky, C. (2008). Collaborative filtering for implicit feedback datasets. In Data Mining, 2008. ICDM’08. Eighth IEEE International Conference on (pp. 263-272). IEEE.  
* Takács, G., Pilászy, I., Németh, B., & Tikk, D. (2009). Scalable collaborative filtering approaches for large recommender systems. Journal of machine learning research, 10(Mar), 623-656.  
* Rendle, S., Freudenthaler, C., Gantner, Z., & Schmidt-Thieme, L. (2009). BPR: Bayesian personalized ranking from implicit feedback. In Proceedings of the Twenty-Fifth Conference on Uncertainty in Artificial Intelligence (pp. 452-461). AUAI Press.
* Koren, Y., Bell, R., & Volinsky, C. (2009). Matrix factorization techniques for recommender systems. Computer, 42(8), 30-37. [pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.441.3234&rep=rep1&type=pdf)
* Pan, R., Zhou, Y., Cao, B., Liu, N. N., Lukose, R., Scholz, M., & Yang, Q. (2008). One-class collaborative filtering. In 2008 Eighth IEEE International Conference on Data Mining (pp. 502-511). IEEE. En este artículo aparecen la derivación y reglas de actualización de los parámetros así como las nociones de AMAN y AMAU.
* Jannach, D., Lerche, L., & Zanker, M. (2018). Recommending based on implicit feedback. In Social Information Access (pp. 510-569). Springer, Cham.
* Srebro, N., & Jaakkola, T. (2003). Weighted low-rank approximations. In Proceedings of the 20th International Conference on Machine Learning (ICML-03) (pp. 720-727). Artículo citado por Pan et al. (2008) indicando detalles de la versión no regularizada que inspira OCCF.
* El siguiente paper es opcional, pero permite entender cómo se deriva <a href="https://www.codecogs.com/eqnedit.php?latex=y_i=(X^TC^iX&plus;&space;\lambda&space;I)^{-1}&space;X^TC^ip(i)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?y_i=(X^TC^iX&plus;&space;\lambda&space;I)^{-1}&space;X^TC^ip(i)" title="y_i=(X^TC^iX+ \lambda I)^{-1} X^TC^ip(i)" /></a> e <a href="https://www.codecogs.com/eqnedit.php?latex=x_u=(Y^TC^uY&plus;&space;\lambda&space;I)^1&space;Y^TC^up(u)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x_u=(Y^TC^uY&plus;&space;\lambda&space;I)^{-1}&space;Y^TC^up(u)" title="x_u=(Y^TC^uY+ \lambda I)^1 Y^TC^up(u)" /></a> del paper de Hu et al.: Takács, G., Pilászy, I., & Tikk, D. (2011). Applications of the conjugate gradient method for implicit feedback collaborative filtering. In Proceedings of the fifth ACM conference on Recommender systems (pp. 297-300). ACM.
* Verstrepen, K., Bhaduriy, K., Cule, B., & Goethals, B. (2017). Collaborative filtering for binary, positiveonly data. ACM Sigkdd Explorations Newsletter, 19(1), 1-21.

### Semana 3 (entrega 22 de abril):

**Obligatorias**  
* Xin, X., Karatzoglou, A., Arapakis, I., & Jose, J. M. (2020, July). Self-supervised reinforcement learning for recommender systems. In Proceedings of the 43rd International ACM SIGIR conference on research and development in Information Retrieval (pp. 931-940).

**Sugeridas**  
* Cañamares, R., Redondo, M., & Castells, P. (2019). Multi-armed recommender system bandit ensembles. In Proceedings of the 13th ACM Conference on Recommender Systems (pp. 432-436).
* Bendada, W., Salha, G., & Bontempelli, T. (2020). Carousel Personalization in Music Streaming Apps with Contextual Bandits. In Fourteenth ACM Conference on Recommender Systems (pp. 420-425).
* Lacerda, A., Santos, R. L., Veloso, A., & Ziviani, N. (2015). Improving daily deals recommendation using explore-then-exploit strategies. Information Retrieval Journal, 18(2), 95-122.
* Guillou, F., Gaudel, R., & Preux, P. (2016). Scalable explore-exploit collaborative filtering. In Pacific Asia Conference On Information Systems (PACIS). Association For Information System.
* Teo, C. H., Nassif, H., Hill, D., Srinivasan, S., Goodman, M., Mohan, V., & Vishwanathan, S. V. N. (2016). Adaptive, personalized diversity for visual discovery. In Proceedings of the 10th ACM conference on recommender systems (pp. 35-38).

<!--
### Semana 4 a 7

Sin lecturas

### Semana 8 (entrega el Lu 30 de Sept)

Xin, X., Karatzoglou, A., Arapakis, I., & Jose, J. M. (2020, July). Self-supervised reinforcement learning for recommender systems. In Proceedings of the 43rd International ACM SIGIR conference on research and development in Information Retrieval (pp. 931-940).

### Semana 9 (entrega el Lu 30 de Sept)

Raghavan, M., Barocas, S., Kleinberg, J., & Levy, K. (2020, January). Mitigating bias in algorithmic hiring: Evaluating claims and practices. In Proceedings of the 2020 conference on fairness, accountability, and transparency (pp. 469-481).

### Semana 10 (entrega el Lu 30 de Sept)

Chang, J., Gao, C., Zheng, Y., Hui, Y., Niu, Y., Song, Y., ... & Li, Y. (2021, July). Sequential recommendation with graph neural networks. In Proceedings of the 44th international ACM SIGIR conference on research and development in information retrieval (pp. 378-387). -->

<!-- ## Lecturas complementarias

### Filtrado basado en contenido

**Obligatorias**  
* Pazzani, M. J., & Billsus, D. (2007). Content-based recommendation systems. In The adaptive web (pp. 325-341). Springer Berlin Heidelberg. Xu, W., Liu, X., & Gong, Y. (2003).[pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.448.662&rep=rep1&type=pdf)

**Sugeridas**  
* Document clustering based on non-negative matrix factorization. In Proceedings of the 26th annual international ACM SIGIR conference on Research and development in informaion retrieval (pp. 267-273). ACM.
* Messina, P., Dominguez, V., Parra, D., Trattner, C., & Soto, A. (2019). Content-based artwork recommendation: integrating painting metadata with neural and manually-engineered visual features. User Modeling and User-Adapted Interaction, 29(2), 251-290.
* Celma, Ò., & Herrera, P. (2008). A new approach to evaluating novel recommendations. In Proceedings of the 2008 ACM conference on Recommender systems (pp. 179-186).
* Van den Oord, A., Dieleman, S., & Schrauwen, B. (2013). Deep content-based music recommendation. In Advances in neural information processing systems (pp. 2643-2651).

### Recomendación sensible al contexto

**Obligatorias (esta semana se puede elegir una de las dos para entregar*)**  
* Adomavicius, G., Mobasher, B., Ricci, F. and Tuzhilin, A. (2011). Context-Aware Recommender Systems. AI Magazine, 32(3), 67-80. 
* Jahrer, M., Töscher, A. and Legenstein, R. (2010). Combining predictions for accurate recommender systems. In Proceedings of the 16th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 693-702. ACM.

**Sugeridas**  
* Pigi K., Shobeir F., James F., Magdalini E. and Lise G. (2015). HyPER: A Flexible and Extensible Probabilistic Framework for Hybrid Recommender Systems. In Proceedings of the 9th ACM Conference on Recommender Systems (RecSys '15), 99–106. ACM. 
* Rendle, S. (2010). Factorization machines. In 2010 IEEE International Conference on Data Mining (pp. 995-1000). IEEE.


### Deep Learning para RecSys

**Obligatorias**
* Hasta la sección 3.4 (incluyendo 3.4) + sección 4: Zhang, S., Yao, L., Sun, A., & Tay, Y. (2019). Deep learning based recommender system: A survey and new perspectives. ACM Computing Surveys (CSUR), 52(1), 1-38.

**Sugeridas**
* Covington, P., Adams, J., & Sargin, E. (2016). Deep neural networks for youtube recommendations. In Proceedings of the 10th ACM conference on recommender systems (pp. 191-198).
* Bansal, T., Belanger, D., & McCallum, A. (2016). Ask the gru: Multi-task learning for deep text recommendations. In Proceedings of the 10th ACM Conference on Recommender Systems (pp. 107-114).
* He, R., & McAuley, J. (2016). VBPR: visual bayesian personalized ranking from implicit feedback. In Proceedings of the AAAI conference on artificial intelligence (Vol. 30, No. 1).

### Interfaces de Usuario y Sistemas Interactivos para RecSys

**Obligatorias**
* He, C., Parra, D., & Verbert, K. (2016). Interactive recommender systems: A survey of the state of the art and future research challenges and opportunities. Expert Systems with Applications, 56, 9-27.
 
**Sugeridas**
* Bostandjiev, S., O'Donovan, J., & Höllerer, T. (2012). TasteWeights: a visual interactive hybrid recommender system. In Proceedings of the sixth ACM conference on Recommender systems (pp. 35-42).
* Knijnenburg, B., Bostandjiev, S., O'Donovan, J., and Kobsa, A. (2012). Inspectability and control in social recommenders. RecSys'12 - Proceedings of the 6th ACM Conference on Recommender Systems. 
* Pu, P., Chen, L. and Hu, R. (2011). A user-centric evaluation framework for recommender systems. RecSys'11 - Proceedings of the 5th ACM Conference on Recommender Systems. 157-164.
* Parra, D., Brusilovsky, P., and Trattner, C. (2014). See What You Want to See: Visual User-Driven Approach for Hybrid Recommendation. International Conference on Intelligent User Interfaces, Proceedings IUI.
* Andjelkovic, I., Parra, D., & O’Donovan, J. (2019). Moodplay: Interactive music recommendation based on Artists’ mood similarity. International Journal of Human-Computer Studies, 121, 142-159.


### Bandidos Multibrazos

**Obligatorias**
* Cañamares, R., Redondo, M., & Castells, P. (2019). Multi-armed recommender system bandit ensembles. In Proceedings of the 13th ACM Conference on Recommender Systems (pp. 432-436).
* Bendada, W., Salha, G., & Bontempelli, T. (2020). Carousel Personalization in Music Streaming Apps with Contextual Bandits. In Fourteenth ACM Conference on Recommender Systems (pp. 420-425).

**Sugeridas**
* Lacerda, A., Santos, R. L., Veloso, A., & Ziviani, N. (2015). Improving daily deals recommendation using explore-then-exploit strategies. Information Retrieval Journal, 18(2), 95-122.
* Guillou, F., Gaudel, R., & Preux, P. (2016). Scalable explore-exploit collaborative filtering. In Pacific Asia Conference On Information Systems (PACIS). Association For Information System.
* Teo, C. H., Nassif, H., Hill, D., Srinivasan, S., Goodman, M., Mohan, V., & Vishwanathan, S. V. N. (2016). Adaptive, personalized diversity for visual discovery. In Proceedings of the 10th ACM conference on recommender systems (pp. 35-38).

### Recomendación secuencial

**Obligatorias**
* Sun, F., Liu, J., Wu, J., Pei, C., Lin, X., Ou, W., & Jiang, P. (2019). BERT4Rec: Sequential recommendation with bidirectional encoder representations from transformer. In Proceedings of the 28th ACM international conference on information and knowledge management (pp. 1441-1450).

**Sugeridas**
* Chen, Q., Zhao, H., Li, W., Huang, P., & Ou, W. (2019). Behavior sequence transformer for e-commerce recommendation in alibaba. In Proceedings of the 1st International Workshop on Deep Learning Practice for High-Dimensional Sparse Data (pp. 1-4).
* Chen, J., Zhang, H., He, X., Nie, L., Liu, W., & Chua, T. S. (2017). Attentive collaborative filtering: Multimedia recommendation with item-and component-level attention. In Proceedings of the 40th International ACM SIGIR conference on Research and Development in Information Retrieval (pp. 335-344).
* Liang, D., Krishnan, R. G., Hoffman, M. D., & Jebara, T. (2018). Variational autoencoders for collaborative
  filtering. In Proceedings of the 2018 World Wide Web Conference (pp. 689-698). -->


