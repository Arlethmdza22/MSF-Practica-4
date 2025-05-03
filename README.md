[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Arlethmdza22/MSF-Practica-4)

# Modelado de Sistemas Fisiológicos. Práctica 4: Sistema Cardiovascular [Mendoza20211984]

## Autor
Mendoza Perez Arleth Alejandra 

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: L20211984@tectijuana.edu.mx

## Objetivos general
Diseñar un controlador que permita formular un protocolo de tratamiento para que un paciente con hipertension (caso) y con hipotension (caso) presente la misma presion cardiaca que un individuo sano (control).

## Actividades
1. Calcular analíticamente la función de transferencia del sistema cardiovascular.

2. Determinar el error en estado estacionario y la estabilidad del sistema en lazo abierto.

3. Construir el diagrama de bloques como se indica en el diagrama 5.8.

4. Diseñar el controlador con Simulink utilizando el bloque *PID Controller* y la herramienta *Tune* para sintonizar los valores óptimos para cada una de las ganancias \(k_P\), \(k_I\) y \(k_D\).

5. Ilustrar el cambio de la presión sobre la distensibilidad arterial \([P_p(t)]\) en respuesta a la presión arterial de entrada \(P_a(t)\). Utilice la función de entrada *Uniform Random Number* con la siguiente configuración: mín = -0.2 V, máx = 1 V, *seed* = 106, *Sample time* = 0.5.

6. Determinar la respuesta a la función en el intervalo \(t \in [0, 15]\) (segundos) en Python, Simulink y Multisim en lazo abierto y en lazo cerrado con el controlador.

7. Elaborar el diagrama fisiologico en biorender.com.

8. Discutir los resultados obtenidos en la experimentacion insilico.

## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus para la asignatura de Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/scl/fi/4gl55ccrjm9yulvziikxs/Modelado-de-Sistemas-Fisiologicos.pdf
