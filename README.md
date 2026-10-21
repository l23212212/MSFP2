[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=l23212212/MSFP2)

# Práctica 2: Sistema Cardiovascular

## Información del estudiante

Diego Macias Armenta [23212212]; l23212212@tectijuana.edu.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México / TecNM - Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1. Modelar la dinámica del sistema cardiovascular mediante el uso de ecuaciones diferenciales ordinarias (EDOs) y analogías eléctricas (parámetros Z, L, R, C).
2. Simular y comparar el comportamiento de la presión arterial en pacientes normotensos, hipotensos e hipertensos.
3. Resolver computacionalmente el modelo de EDOs implementando métodos numéricos en funciones de MATLAB.
4. Sintonizar e implementar un controlador PID en Simulink/MATLAB para corregir los estados de hipotensión e hipertensión, llevando la respuesta hacia el estado normotenso.
5. Graficar y analizar las respuestas hemodinámicas con el controlador PID en operación frente al comportamiento patológico en lazo abierto.

## Descripción detallada del sistema

En esta práctica se aborda el modelado computacional del sistema cardiovascular utilizando una aproximación basada en EDOs (Ecuaciones Diferenciales Ordinarias). Mediante la variación de los parámetros de impedancia, inductancia, resistencia y capacitancia hemodinámica (Z, L, R, C), se emulan tres escenarios clínicos distintos: un paciente con presión arterial normal (Normotenso), presión arterial baja (Hipotenso) y presión arterial alta (Hipertenso). Asimismo, se diseña y valida el uso de un controlador PID capaz de regular la respuesta patológica (hipo/hipertensa) para lograr que siga la dinámica deseada del individuo normotenso de referencia.

Palabras clave: Sistema cardiovascular; Controlador PID; Ecuaciones Diferenciales Ordinarias; Presión arterial.

## Lista de archivos incluidos en el repositorio

1. Scripts de MATLAB para inicialización de parámetros, resolución del modelo de EDOs y graficación `plotsignals` [`.m` o `.mlx`].
2. Modelo de Simulink del sistema cardiovascular y los controladores PID `Practica2.slx` [`.slx`].
3. Archivo de datos extraído de la simulación `signal.xlsx` [`.xlsx`].
4. Imágenes de las simulaciones y comparativas (Hipotenso vs Normotenso vs PID, etc.) [`.pdf` y `.png`].

## Referencias

[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018.

[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley & Sons, 2020.
