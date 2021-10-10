# Clasificador-para-datos-tabulares-de-Alzheimer
Primer Proyecto de la materia de 'Proyecto integrador de tecnologías emergentes' impartida por el profesor Daniel Cabrera  

Equipo #3  
María Fernanda Mendoza A01745728  
Carolina Obregon A01251983  
Isabel Navarro A00823132  
Jaime Montemayor A01176573  
Gustavo De Los Ríos Alatorre A01410922  

## Introducción
La enfermedad de Alzheimer consta de un trastorno neurológico progresivo que provoca el encogimiento del cerebro (atrofia), provocando también el la muerte de las neuronas en el paciente.

Esta enfermedad es el tipo de demencia más frecuente, conlleva un deterioro continuo en el pensamiento, comportamiento, y habilidades sociales afectando la independencia de aquellos que la padecen.

Actualmente, en EEUU, unos 5.8 millones de personas de 65 años o más viven con la enfermedad. De ellas el 85% tiene 75 años o más. De los aproximadamente 50 millones de personas con demencia en todo el mundo, se estima que entre 60% y 70% padecen la enfermedad de acuerdo con la [Mayo Clinic](https://www.mayoclinic.org/es-es/diseases-conditions/alzheimers-disease/symptoms-causes/syc-20350447).

En [Demencias una visión panorámica](http://www.geriatria.salud.gob.mx/descargas/publicaciones/Demencia.pdf), reporte del quinto simposio de médicina geriátrica realizado en la Universidad Autónoma de San Luis Potosí. Se estima que para el año 2050, la cifra de mexicanos afectados por la enfermedad de Alzheimer, será de más de 3.5 millones de personas.

Debido a que esta es una enfermedad progresiva, los síntomas de esta en etapas tempranas frecuentemente son difíciles de detectar ya que comienza con algo aparentemente común, cómo el momentaneamente olvidarse de ciertas cosas. Es por esta razón que hemos decidido ensamblar un modelo para datos tabulares que sea capaz de asistir en la detección temprana del Alzheimer.
## Requerimientos
**Se debe de ejectuar el código en Google Colab para asegurar su funcionamiento adecuado.**

Librerias utilizadas:
- pandas
- seaborn
- plotly
- sklearn
- itertools
- numpy
- matplotlib
- statsmodels
- warnings
- lightgmb

## Uso del código
El archivo final del modelo: ___.ipynb

Al realizar el clone al repositorio se obtienen todos los archivos, en caso de no hacerlo, verificar que se tengan todos los archivos de los datos para su correcto funcionamiento.

## Clonado del repositorio
```
https://github.com/GustavoDLRA/Clasificador-para-datos-tabulares-de-Alzheimer.git
```
## Base de datos
OASIS Longitudinal Dataset
El proyecto Open Access Series of Imaging Studies (OASIS) tiene el objetivo de proporcionar sets de datos de resonancia magnética del cerebro a la comunidad científica.

OASIS existe gracias al Centro de Investigación de la Enfermedad de Alzheimer de la Universidad de Washington Dr. Randy Buckner en el Instituto Médico Howard Hughes (en la Universidad de Harvard, el grupo de Investigación Neuroimformática de la escuela de medicina de la Universidad de Washington y el centro de investigación de informática biomédica).

El [OASIS Longitudinal Dataset](https://www.kaggle.com/jboysen/mri-and-alzheimers?select=oasis_longitudinal.csv) en particular, consiste en una colección longitudinal de 150 sujetos de entre 60 y 96 años de edad. Cada sujeto fue escaneado en dos o más visitas separadas por al menos un año. Se cuenta con un total de 373 sesiones de imagen.

## Descripción y entrenamiento de los modelos
## Resultados
![image](https://user-images.githubusercontent.com/23626475/136715148-bff5bb2a-2298-4d28-8007-f49f67dddd0b.png)

## Páginas consultadas
- Brosch, JR, et al. Early-onset dementia in adults. https://www.uptodate.com/contents/search. Accessed Dec. 4, 2019.
- M. Tanveer, B. Richhariya, R.U. Khan, A.H. Rashid, P. Khanna, M. Prasad, and C.T. Lin. 2020. Machine learning techniques for the diagnosis of Alzheimer’s disease: A review. ACM Trans. Multimedia Comput. Commun. Appl. 16, 1s, Article 30 (April 2020), 28 pages. https://doi.org/https://doi.org/10.1145/3344998
