[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=KeybinSanchez/MSFPractica1)

# Práctica 3: Sistema musculoesquelético

## Información de la estudiante

Sanchez Perez Keybin Daniel \[23210721]; l23210721@tectijuana.edu.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1. Calcular la función de transferencia del modelo biomecánico del sistema musculoesquelético representado mediante un circuito RLC de segundo orden.
2. Determinar el modelo de ecuaciones integro-diferenciales.
3. Calcular el error en estado estacionario y la estabilidad del sistema.
4. Emular y simular la respuesta del circuito en Simulink/Simscape.
5. Sintonizar las ganancias de un controlador PID para regular la posición o fuerza del segmento musculoesquelético.
6. Obtener la respuesta en lazo abierto y en lazo cerrado con el controlador PID en Spyder/Python.
7. Elaborar el diagrama del sistema.

## Descripción detallada del sistema

El sistema musculoesquelético puede modelarse mediante analogías eléctricas que capturan sus propiedades viscoelásticas e inerciales. Un modelo simplificado de segundo orden, representado por un circuito RLC en serie, permite describir la dinámica de un segmento corporal o de una articulación sometida a fuerzas externas o activación muscular:

1. Resistencia (R): Representa la fricción y la viscosidad de los tejidos (músculos, tendones, ligamentos y cartílago) que disipan energía durante el movimiento. Corresponde al amortiguamiento del sistema.

2. Inductancia (L): Representa la inercia del segmento corporal, es decir, la resistencia al cambio en la velocidad (masa inercial).

3. Capacitancia (C): Representa la compliancia o elasticidad de los tejidos (por ejemplo, la distensibilidad de los tendones y la capacidad de almacenar energía elástica).

La entrada al sistema puede ser la fuerza muscular generada o una fuerza externa aplicada F(t), y la salida puede ser el desplazamiento x(t) o el ángulo articular. Este modelo es análogo al de un sistema masa-resorte-amortiguador, ampliamente utilizado en biomecánica para estudiar la respuesta del sistema musculoesquelético ante perturbaciones, el control postural y el diseño de prótesis u órtesis.

## Palabras clave
Sistema Musculoesquelético; Circuito RLC; Controlador PID; Modelo biomecánico; Simulaciones numéricas, Fuerza-Voltake.

## Lista de archivos incluidos en el repositorio

1. Cuaderno computacional de MATLAB \[.mlx].
2. Modelo de Simulink \[.slx].
3. Archivos de Spyder \[.py].
4. Imagen con los parámetros del controlador.
5. Imágenes de las simulaciones \[.pdf].
6. Evidencia del análisis matemático: función de transferencia, modelo de ecuaciones integro-diferenciales, error en estado estacionario y estabilidad en lazo abierto.
7. Modelo fisiológico en Biorender o BioArt.

## Referencias

\[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

\[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 4, Page 93.

\[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley \& Sons, 2020.

\[4] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 2, Page 26.

