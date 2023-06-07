# Técnicas de Análisis de EMG en la Enfermedad de Parkinson 
Este repositorio contiene análisis de registros de electromiografía (EMG) de superficie en un paciente con la Enfermedad de Parkinson (EP) juvenil. La finalidad de la técnica de electromiografía de superficie, la cual no es una prueba invasiva, sirve para diagnosticar padecimientos relacionados con la actividad eléctrica de los músculos o cómo interactúan las unidades motoras entre sí.

Se elaboraron notebooks de diversos procesamientos de señales de la EP juvenil. La finalidad de la creación de este repositorio es contribuir con registros de la EP y análisis de señales para ampliar el campo de estudio en temas relacionados con la electrofisiología. En este repositorio encontrarás:
##
## Obtención & visualización de señales electromiográficas en Parkinson.
**Registros del miembro superior**: para estas pruebas se registraron músculos en relajación, esfuerzo o con algún ejercicio. 
  
  -*Bíceps*.
  
  -*Tríceps*.
  
  -*Músculos del antebrazo*.
  
  -*Músculos de la mano*. 

**Registros de miembro inferior**: para esta prueba solo se registró en la parte posterior de la pierna, también se registró cuando estaba en relajación y esfuerzo. 

  -*Pantorrilla*. 
  
**Registros del paciente control (sin la Enfermedad de Parkinson)**: se repitieron las mismas pruebas, para comparar el los registros de señales anómalas y señales control. 
## 
También encontrarás registros de EMG cuando el paciente tiene latentes los estímulos producidos por la Enfermedad de Parkinson, debido a que se encontraba bajo los efectos del medicamento promotor de dopamina. Por otro lado, se registraron los músculos cuando el paciente tiene un lapso sin medicamento, entonces, las señales muestran diferencias entre las ***electromiografías con medicamento y sin medicamento***.
##
## Análisis con filtros
  -*Filtro Butterworth de paso bajo*.
  
  -*Filtro pasa bajas, pasa altas y pasa bandas*.
  
  -*Filtro Notch*.
  
  -*Filtro con filtfilt o lfilter*.
  
  -*Filtro Mediano*.
  
  -*Filtro Wiener*.
  
  -*Filtro Savitzky-Golay*.
## 
## Cuantificación y análisis  de señales

Se obtuvo la envoltura, rectificación, amplitud máxima, densidad espectral, área, detección de eventos (cuando inicia y termina un estímulo). 
##
## Análisis espectral

Mediante el análisis espectral de Fourier podemos analizar una serie de tiempo pero en el dominio de la frecuencia, debido a que todos los análisis anteriores se han desarrollado hasta el momento son análisis en el dominio del tiempo. Se obtuvieron espectrogramas de señales significativas.
##
****En caso de sugerir mejoras o tener preguntas de la elaboración de este proyecto, pueden comunicarse:****

elliotflooli@ciencias.unam.mx
