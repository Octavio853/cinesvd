# CineSVD

Juego interactivo que muestra cómo funciona un sistema de recomendación con **PureSVD** sobre MovieLens 1M (6.040 usuarios, 3.706 películas).

**Jugar:** https://octavio853.github.io/cinesvd/

Calificás algunas películas y el sistema calcula tus recomendaciones con `s = r V Vᵀ`, donde `V` son los primeros 50 vectores singulares derechos de la matriz de calificaciones. Abajo hay un paso a paso interactivo de cómo se pasa de matriz en matriz.

Trabajo final de Análisis Matricial.

Datos: MovieLens 1M, GroupLens Research, Universidad de Minnesota. F. M. Harper y J. A. Konstan (2015), *The MovieLens Datasets: History and Context*, ACM TiiS 5(4).
