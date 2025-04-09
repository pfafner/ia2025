# Inteligencia Artificial 2025

Este es un curso introductorio a la inteligencia artificial, la cual es un área donde se mezclan muchas disciplinas: lógica, programación, matemática, estadística, probabilidad, algoritmos, entre otros. El objetivo del curso es aprender los fundamentos de la inteligencia artificial. El curso comienza haciendo una revisión histórica de diferentes campos de aplicación del área, para luego entrar en los conceptos fundamentales como agentes, espacios de configuraciones y espacios de estados. 

Seguidamente, introducimos el tipo más simple de agentes, mediante el estudio de modelos de aprendizaje automática. Mencionamos generalidades sobre diferentes modelos de agrupamiento, clasificación y regresión. Hacemos énfasis en las métricas de evaluación y técnicas para mejorar el desempeño de los modelos. 

Después, el curso hace una revisión de diferentes algoritmos de búsqueda como BFS, DFS, y *backtracking*, entre otros, así como el desarrollo de heurísticas, como el algoritmos A* y algunos métodos de optimización combinatoria: algoritmos genéticos, evolución diferencial o *particle swarm optimization*. Hacemos una introducción a los métodos de búsqueda adversaria, principalmente las técnicas de *minimax*, *expectimax* y *expectiminimax*, vemos la comparación y análisis de complejidad de estos métodos de búsqueda, y técnicas de reducción como el $\alpha$-$\beta$ *prunning*.

Luego, combinamos estos conocimientos con el área de probabilidad, para estimar incertidumbre en los modelos de búsqueda. Desarrollaremos métodos de redes bayesianas, y modelos ocultos de Markov y abordaremos tópicos básicos sobre aprendizaje por refuerzo.

El curso requiere madurez por parte del estudiante, pues se integran contenidos de muchos cursos de computación, matemática y estadística. Entre los prerrequisitos se encuentra tener un buen dominio de las técnicas vistas en los cursos de matemática discreta, grafos, lógica, programación y algoritmos, cálculo, álgebra lineal, probabilidad y estadística. 


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-ia2025.pdf){:target="_blank"}

### Horario
<div id='id-horario'/>

* Lunes, de 17:20 a 19:45 horas, Miércoles, de 17:20 a 19:00 horas.

### Office Hours
<div id='id-office'/>

* Por definir. Por solicitud del estudiante. También pueden enviar sus dudas por correo electrónico.


# Material del curso
<div id='id-material'/>

**No.**  | **Fecha**    | **Tópicos**                                                       | **Recursos**
-------- | ------------ | ----------------------------------------------------------------- |  -------------------------------------
01       | 13.01.2025   | Inicio del curso. <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"} [Aula 02](aulas/Aula02.pdf){:target="_blank"} | [Wordcloud](otros/wordcloud.png){:target="_blank"} 
02       | 15.01.2025   | Agentes. Secuencias de percepción. Ejemplos. <br/> | 
03       | 20.01.2025   | Ambientes. Tipos de agentes. <br/> [Aula 03](aulas/Aula03.pdf){:target="_blank"} | [Descripción de Agentes.xlsx](otros/Descripcio%CC%81n%20de%20Agentes.xlsx){:target="_blank"} <br/> [Clasificación de Ambientes.xlsx](otros/Clasificacio%CC%81n%20de%20Ambientes.xlsx){:target="_blank"} 
04       | 22.01.2025   | Distribuciones. Densidad y función de distribución. [Aula 04](aulas/Aula04.pdf){:target="_blank"} | [rvs.ipynb](code/rvs.ipynb){:target="_blank"} [exploration.ipynb](code/exploration.ipynb){:target="_blank"} 
05       | 27.01.2025   | Gráficos de probabilidad. Ajuste y contraste de distribuciones. [Aula 05](aulas/Aula05.pdf){:target="_blank"} | [qqplots.ipynb](code/qqplots.ipynb){:target="_blank"} [fitting.ipynb](code/fitting.ipynb){:target="_blank"} 
06       | 27.01.2025   | Estadísticos. Distribuciones multivariadas. [Aula 06](aulas/Aula06.pdf){:target="_blank"} | [center-data.ipynb](code/center-data.ipynb){:target="_blank"} 
07       | 03.02.2025   | Generación de normal multivariada. <br/> | [generate_gaussian.ipynb](code/generate_gaussian.ipynb){:target="_blank"} [svd.ipynb](code/svd.ipynb){:target="_blank"} 
08       | 03.02.2025   | Análisis de componentes principales (PCA). Interpretación. [Aula 07](aulas/Aula07.pdf){:target="_blank"} [Aula 08](aulas/Aula08.pdf){:target="_blank"} | [pca.ipynb](code/pca.ipynb){:target="_blank"}  
09       | 05.02.2025   | Compresión de imágenes con PCA. <br/>  |  [SVD Compression Demo](http://timbaumann.info/svd-image-compression-demo/){:target="_blank"} 
L2       | 05.02.2025   | Lab 2. **Entrega: 12 de febrero.** | [areas.csv](labs/areas.csv){:target="_blank"} [weather.csv](labs/weather.csv){:target="_blank"} <br/> [Lab 2](labs/lab02.pdf){:target="_blank"}   
10       | 10.02.2025   | Agrupamiento Jerárquico. <br/> [Aula 09](aulas/Aula09.pdf){:target="_blank"} | 
11       | 10.02.2025   | Algoritmo *K-means* y variantes. Aplicaciones. <br/> [Aula 10](aulas/Aula10.pdf){:target="_blank"} | 
12       | 12.02.2025   | Algoritmos basados en densidad: Mean-shift, DBSCAN, OPTICS, BIRCH. [Aula 11](aulas/Aula11.pdf){:target="_blank"} | 
13       | 17.02.2025   | Modelación predictiva: clasificación y regresión. Algoritmo KNN. [Aula 12](aulas/Aula12.pdf){:target="_blank"} | 
14       | 19.02.2025   | Clasificador bayesiano. Naïve Bayes. <br/>  | 
15       | 24.02.2025   | Ejemplos de Naïve Bayes. Clasificadores lineales. | 
16       | 26.02.2025   | Regresión logística. Perceptrón. Redes neuronales. | 
17       | 03.03.2025   | Ejemplo de red neuronal para regresión. <br/>  | 
18       | 03.03.2025   | Problemas de búsqueda. <br/>  | 
19       | 10.03.2025   | Representación de problemas de búsqueda.  |  
L3       | 10.03.2025   | Lab 3. **Entrega: 17 de marzo.** | [Lab 3](labs/lab03.pdf){:target="_blank"}   
20       | 12.03.2025   | Grafo de estados. Árbol de búsqueda. <br/>  |  
21       | 12.03.2025   | Algoritmos de búsqueda: DFS y BFS. <br/> [Aula 20](aulas/Aula20.pdf){:target="_blank"} |  
22       | 17.03.2025   | Más algoritmos de búsqueda. Búsqueda por costo uniforme. Ejemplos. [Aula 21](aulas/Aula21.pdf){:target="_blank"} |  
L4       | 17.03.2025   | Lab 4. **Entrega: 31 de marzo.** | [Lab 4](labs/lab04.pdf){:target="_blank"}   
23       | 19.03.2025   | Heurísticas. Algoritmos Greedy y A*. <br/> [Aula 22](aulas/Aula22.pdf){:target="_blank"} |  
24       | 24.03.2025   | Presentación del Proyecto 1. <br/> |  
25       | 24.03.2025   | Laboratorio sobre métodos de búsqueda y A*. <br/> |  
26       | 02.04.2025   | Árbol de expansión. Algoritmo de Kruskal y algoritmo de Prim.  |  
27       | 07.04.2025   | Búsqueda con restricciones. *Backtracking*. Filtrado y consistencia por arcos.  |  


# Proyectos del Curso
<div id='id-proj'/>

En el curso se trabajarán 4 proyectos, los cuales se indicarán más adelante.

## Proyecto 1 (Machine Learning)
<div id='id-proj1'/>

**No.**  | **Fecha**    | **Tópicos**                                   | **Recursos**
-------- | ------------ | --------------------------------------------- |  -------------------------------------
 1       | 24.02.2025   | Proyecto 1 - *Machine Learning*.              | [Proyecto 1](proyectos/Proyecto1.pdf){:target="_blank"} <br/> 
 2       | 17.03.2025   | Entrega del proyecto.                         | 
 3       | 21.03.2025   | Entrega del informe y código.                 | 


## Proyecto 2 (Algoritmos de búsqueda)
<div id='id-proj2'/>

**No.**  | **Fecha**    | **Tópicos**                                   | **Recursos**
-------- | ------------ | --------------------------------------------- |  -------------------------------------
 1       | 08.04.2025   | Proyecto 2 - *Búsqueda*.                      | [Proyecto 2](proyectos/Proyecto2.pdf){:target="_blank"} <br/> 
 2       | 12.05.2025   | Entrega del proyecto.                         | 
 3       | 16.05.2025   | Entrega del informe y código.                 | 


# Referencias
<div id='id-ref'/>

### Textos:

* [S. Russell y P. Norvig (2021). *Artificial Intelligence: A Modern Approach*. 4a ed.](https://libgen.li/ads188ec1f979f92af02697f4066f3dd93a264NWNFJ){:target="_blank"}

* [S. Russell y P. Norvig (2013). *Inteligencia Artificial: Un enfoque moderno*. 2a ed.](https://libgen.li/ads6b862ce758b8513e6d5627895d2bfc3dTZVFFXU8){:target="_blank"}


---
