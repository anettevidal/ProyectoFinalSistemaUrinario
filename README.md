[[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=anettevidal/ProyectoFinalSistemaUrinario)]

# Proyecto final: Sistema urinario masculino.

## Información de los estudiantes

Cristina Lopez Lopez [22212259]; l22212259@tectijuana.edu.mx.

Ximena Solis Marrufo [22212274]; l22212274@tectijuana.edu.mx.

Anette Mariana Vidal Ortiz [22212389]; l22212389@tectijuana.edu.mx.

Alberto Villalobos Valdez [22212277]; l22212277@tectijuana.edu.mx.


Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos
1. Calcular función de transferencia, modelo de ecuaciones integrales-diferenciales, error estacionario y estabilidad en lazo abierto.
2. Analizar el impacto de la infección urinaria en la dinámica del flujo urinario en la gráfica.
3. Simular y predecir el comportamiento del sistema urinario mediante un circuito RLC.

 

## Descripción detallada del sistema

El sistema urinario, en particular el transporte de la orina desde los riñones hasta la vejiga y su posterior expulsión por la uretra, puede representarse de forma simplificada mediante un circuito eléctrico de segundo orden. 
Para describir este sistema mediante un circuito RLC de dos mallas, se consideran las siguientes correspondencias fisiológicas:
*Resistencia al flujo urinario (R).
La fricción del flujo de orina dentro de los uréteres se modela mediante un resistencia R. Este elemento representa la oposición que encuentran los riñones para transportar la orina hacia la vejiga.

*Inercia de la orina en movimiento (L).
La masa del fluido urinario que se desplaza a través de los uréteres se modela con un inductor L. Este componente refleja la dificultad del sistema para cambiar rápidamente la velocidad del flujo urinario.

*Capacidad de almacenamiento de la vejiga (Cv).
La distensibilidad de la vejiga, que permite almacenar orina antes de ser expulsada, se representa mediante un capacitor Cv. Este elemento modela cómo aumenta la presión vesical a medida que se acumula mayor volumen.

*Resistencia uretral (Rp).
La oposición al flujo de salida de la orina durante la micción se modela mediante un resistor Rp, que representa la resistencia anatómica de la uretra.
La señal de entrada Ve(t) corresponde a la presión generada por los riñones, la cual impulsa continuamente la orina hacia la vejiga. Esta señal puede representarse como una variación suave o periódica en la filtración renal.

La señal que va a representar el sistema va a ser la sinusoidal.

La infección urinaria baja ocasiona inflamación en la uretra y, en algunos casos, irritación en la vejiga. En el modelo eléctrico, esta condición se representa mediante:
Aumento de la resistencia uretral Rp debido al estrechamiento del conducto por inflamación.
Aumento leve de la resistencia uretral R si la infección genera presión retrógrada hacia los uréteres.
Disminución de la capacitancia vesical Cv, ya que la vejiga irritada es menos capaz de almacenar volumen sin aumento de presión.
La inductancia L se mantiene sin cambios, pues la inercia de la orina no se modifica con esta patología.


Palabras clave: Infección urinaria; Sistema Urinario; Modelo matemático; Controlador I; Circuito RLC.

## Lista de archivos incluidos en el repositorio
1. Cuaderno computacional de MATLAB \[.mlx].
2. Imágenes de las simulaciones \[.pdf y .png].
3. Modelo de Simulink [.slx].
4. Imagen de los parámetrros del controlador PID.
5. Imágenes del análisis matemático en cuaderno.

## Referencias

[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/
[2] Sistema urinario. (2025). Kenhub. https://www.kenhub.com/es/library/anatomia-es/sistema-urinario

‌

