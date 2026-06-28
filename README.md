# Análisis de Señales en el Dominio del Tiempo y la Frecuencia utilizando MATLAB

## Introducción

La Transformada de Fourier es una herramienta matemática utilizada para analizar señales y sistemas. Su principal función es transformar una señal del dominio del tiempo al dominio de la frecuencia, permitiendo identificar las componentes frecuenciales que la conforman.

En esta práctica se utilizó MATLAB para generar diferentes señales, visualizar su comportamiento temporal y obtener sus espectros de frecuencia mediante la función FFT (Fast Fourier Transform). Asimismo, se analizaron algunas propiedades fundamentales de la Transformada de Fourier, como la linealidad, el desplazamiento temporal y el escalamiento en frecuencia.

## Desarrollo de la actividad

### Herramienta utilizada

Para la realización de la práctica se empleó MATLAB Online, aprovechando sus funciones de procesamiento de señales y visualización gráfica.

### Señales analizadas

Se generaron las siguientes señales:

* Señal senoidal de 50 Hz.
* Pulso rectangular.
* Función escalón.

Cada señal fue representada en el dominio del tiempo para observar su comportamiento y posteriormente transformada al dominio de la frecuencia utilizando la función FFT.

### Transformada de Fourier

La Transformada Rápida de Fourier (FFT) se aplicó a cada una de las señales con el objetivo de obtener su espectro de frecuencia.

La función utilizada fue:

fft()

La FFT permite identificar las frecuencias dominantes presentes en una señal y estudiar cómo se distribuye su energía en el dominio frecuencial.

## Resultados obtenidos

### Señal senoidal

En el dominio del tiempo se observó una señal periódica con frecuencia de 50 Hz. En el dominio de la frecuencia apareció un pico dominante alrededor de dicha frecuencia, lo que confirma que la señal está compuesta principalmente por una única componente frecuencial.

### Pulso rectangular

El pulso rectangular presentó una duración limitada en el tiempo. Su espectro mostró múltiples componentes frecuenciales distribuidas en diferentes frecuencias, evidenciando que este tipo de señal requiere una combinación de varias frecuencias para su representación.

### Función escalón

La función escalón mostró una transición brusca de amplitud. Su espectro se concentró principalmente en bajas frecuencias, aunque también aparecieron componentes adicionales debido a la discontinuidad de la señal.

## Verificación de propiedades de la Transformada de Fourier

### Propiedad de linealidad

Se sumaron dos señales senoidales de diferentes frecuencias y se observó que el espectro resultante contenía ambas componentes frecuenciales. Esto confirma la propiedad de linealidad de la Transformada de Fourier.

### Desplazamiento temporal

Se desplazó una señal senoidal en el tiempo y se comprobó que la magnitud del espectro permaneció prácticamente constante mientras que la fase sufrió modificaciones.

### Escalamiento en frecuencia

Al modificar la frecuencia de la señal senoidal se observó un desplazamiento de los picos espectrales hacia frecuencias más altas, verificando la propiedad de escalamiento.

## Análisis comparativo

El análisis realizado permitió observar que una misma señal puede presentar comportamientos muy diferentes dependiendo del dominio en el que se estudie.

Mientras que el dominio del tiempo muestra la evolución de la amplitud de la señal, el dominio de la frecuencia permite identificar las componentes frecuenciales responsables de dicha forma de onda.

Las señales simples, como la senoidal, presentan espectros concentrados en pocas frecuencias, mientras que señales con cambios abruptos, como el pulso rectangular y la función escalón, generan espectros más amplios.

## Conclusiones

La práctica permitió comprender la importancia de la Transformada de Fourier en el análisis de señales. Mediante MATLAB fue posible visualizar las señales tanto en el dominio del tiempo como en el dominio de la frecuencia y verificar experimentalmente varias de sus propiedades fundamentales.

Los resultados obtenidos demostraron que la FFT es una herramienta eficiente para identificar componentes frecuenciales y estudiar el comportamiento de diferentes tipos de señales. Además, se comprobó que las propiedades de linealidad, desplazamiento temporal y escalamiento en frecuencia tienen un efecto directo sobre la representación espectral de las señales analizadas.
