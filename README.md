# Laboratorio-Procesamiento_5


## Integrantes
* Marya Kathalina Prieto (5600)
* Maria Jose Romero (5600868)

## Objetivos

Analizar la variabilidad de la frecuencia cardíaca (HRV) mediante la adquisición, procesamiento y análisis de señales ECG, evaluando los cambios en la actividad simpática y parasimpática del sistema nervioso autónomo a través de parámetros temporales y diagramas de Poincaré.

# **Parte A**

## a. Fundamento Teórico

### **Actividad Simpática y Parasimpática del Sistema Nervioso Autónomo**

El sistema nervioso autónomo (SNA) es la parte del sistema nervioso encargada de controlar funciones involuntarias del cuerpo, es decir, aquellas que ocurren automáticamente sin que la persona tenga que pensarlo conscientemente. Entre estas funciones se encuentran:

* La respiración
* La digestión
* La presión arterial
* La temperatura corporal
* La frecuencia cardíaca

> #### **Sistema Nervioso Simpático (SNS)**
El sistema nervioso simpático prepara al organismo para responder ante situaciones de estrés, alerta o actividad física. Esta respuesta se conoce como “lucha o huida”.

**Funciones principales**
* Aumenta la frecuencia cardíaca.
* Aumenta la presión arterial.
* Dilata las pupilas.
* Dilata los bronquios.
* Disminuye la actividad digestiva.
  
**Neurotransmisores del sistema simpático**
***Acetilcolina***

Es liberada por las neuronas preganglionares simpáticas y transmite el impulso hacia los ganglios autónomos.

***Noradrenalina***

Es el principal neurotransmisor posganglionar simpático. 
Produce el aumento de la frecuencia cardíaca, el aumento de la presión arterial y la activación general del organismo.

***Adrenalina***

Liberada por la médula suprarrenal. Refuerza la respuesta simpática del cuerpo.

**Balance Autonomico**
El balance autonómico corresponde al equilibrio entre la actividad simpática y parasimpática.

* Si predomina el sistema simpático → el organismo entra en estado de alerta.
* Si predomina el sistema parasimpático → el organismo entra en estado de relajación.

La HRV permite estudiar este equilibrio mediante el análisis de los intervalos entre latidos cardíacos.

### **Efecto de actividad Simpática y Parásimpatica en la frecuencia cardíaca**

El **sistema nervioso simpático** se activa en situaciones de estrés, alerta, ejercicio o ansiedad. Su función es preparar al organismo para responder rápidamente ante una situación de demanda física o emocional. Cuando se activa, aumenta la frecuencia cardíaca mediante la liberación de neurotransmisores como la noradrenalina y la adrenalina, haciendo que el corazón lata más rápido y disminuyendo el tiempo entre los intervalos R-R.

El **sistema nervioso parasimpático** predomina en estados de reposo y relajación. Su función principal es conservar energía y mantener el equilibrio del organismo. Actúa disminuyendo la frecuencia cardíaca mediante la liberación de acetilcolina, lo que hace que el corazón lata más lentamente y aumente el tiempo entre los intervalos R-R.

### **Variabilidad de la Frecuencia Cardíaca (HRV) a partir de un ECG**

La HRV se obtiene a partir de la señal electrocardiográfica (ECG), la cual registra la actividad eléctrica del corazón. Dentro de la señal ECG, el complejo QRS representa la despolarización de los ventrículos, y el pico de mayor amplitud corresponde al pico R. Midiendo el tiempo entre un pico R y el siguiente se obtienen los intervalos R-R.

La HRV es utilizada para analizar el balance autonómico del organismo:

* El sistema nervioso simpático tiende a disminuir la variabilidad cardíaca y aumentar la frecuencia cardíaca.
* El sistema nervioso parasimpático incrementa la variabilidad y disminuye la frecuencia cardíaca.

Por esta razón, la HRV es considerada un indicador no invasivo del funcionamiento cardíaco y del estado fisiológico del individuo.

Calcular la HRV a partir de un ECG se basa en realizar análisis tanto en el dominio del tiempo como en el de la frecuencia partiendo de la obtención de parámetros relevantes de la señal:

1. **Detección de Picos R:** Máximos del complejo QRS.
2. **Extracción intervalos R-R:** En milisegundos ($ms$).

### **Diagrama de Poincaré; análisis de series R-R**


## b. Adquisición de la señal ECG

La adquisición de la señal ECG consistio en registrar la actividad eléctrica del corazón utilizando electrodos colocados sobre la piel y con un sistema de adquisición de datos. El objetivo fue obtener una señal adecuada para luego analizar la variabilidad de la frecuencia cardíaca (HRV). Se selecciono un sujeto de prueba y registramos la señal ECG durante 4 minutos:

* Los primeros 2 minutos permanecio en reposo, inmóvil y en silencio.
* Los últimos 2 minutos leyo un texto en voz alta.

Esto lo realizamos para comparar el cambio en la actividad del sistema nervioso autónomo entre un estado de relajación y uno de actividad verbal.

# **Parte B**
## c. Pre-procesamiento de la señal

### 1. Filtro HP IIR 

>### 1.1. Diseño del Filtro

>### Ecuación en Diferencias

>### 1.2. Implementación en Python

### 2. Filtro LP IIR 

>### 2.1. Diseño del Filtro

>### Ecuación en Diferencias

>### 2.2. Implementación en Python

### 3. Aplicación de los Filtros

### 4. Segmentación de la señal

> ### División de la señal


## d. Análisis de la HRV en el dominio del tiempo 


> ### Resultados y Gráfica

# **Parte C**

## e. Diagrama de Poincare

> ## Análisis

# **Conclusiones**


