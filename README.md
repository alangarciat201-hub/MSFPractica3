[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=alangarciat201-hub/MSFPractica3)
# MSFPractica3
Practica 3: Sistema musculoesqueletico

## Información de la estudiante

Alan Omar Garcia Toledo, 20210787, alan.garciat201@tectijuana.edu.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1\. Desarrollar el modelo matemático del sistema musculoesquelético.
2. Obtener la función de transferencia del sistema.
3. Analizar la respuesta dinámica del sistema ante una señal de entrada.
4. Simular el comportamiento del sistema en lazo abierto.
5. Diseñar un controlador PID para mejorar la respuesta del sistema.
6. Comparar el comportamiento entre el individuo sano (control) y el caso patológico.

## Descripción detallada del sistema

El sistema musculoesquelético puede representarse mediante una analogía eléctrica de tipo RC, en la cual los elementos resistivos modelan la oposición al movimiento, mientras que los capacitores describen la capacidad de almacenamiento de energía del tejido muscular.

Dentro de este enfoque, la señal de entrada corresponde a una fuerza aplicada 𝐹(𝑡), que induce una respuesta dinámica asociada al proceso de contracción muscular. Las diferencias entre un individuo sano y un paciente con alteraciones musculares se manifiestan principalmente en el valor de la resistencia equivalente del sistema, lo cual modifica la constante de tiempo y, en consecuencia, la velocidad de respuesta del modelo.

El sistema exhibe un comportamiento dinámico de primer orden, donde el caso patológico presenta una respuesta más lenta y con mayor amortiguamiento en comparación con el caso de control. La incorporación de un controlador PID permite compensar estas variaciones, logrando que la respuesta del sistema se aproxime al comportamiento fisiológico normal.

## Lista de archivos incluidos en el repositorio

1\. Cuaderno computacional de MATLAB \[.mlx].
2\. Modelo de Simulink \[.slx].
3. Archivo de Spyder \[.py].
4. Imágenes de las graficas control vs caso \[.pdf].
6. Evidencia del análisis matemático.

7\. Modelo fisiológico en Biorender o BioArt.

## Referencias

\[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

\[2] M. C. Khoo, Physiological Control Systems Analysis, Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 2, Page 26.

\[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley & Sons, 2020.

\[4] T. Kind, T. J. Faes, J. W. Lankhaar, A. Vonk-Noordegraaf & M. Verhaegen, "Estimation of three- and four-element Windkessel parameters using subspace model identification", IEEE Transactions on Biomedical Engineering, vol. 57, no. 7, pp. 1531–1538, Jul 2010. https://doi.org/10.1109/TBME.2010.2041351
