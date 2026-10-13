# Nombre del proyecto
Generación de informes clínicos sintéticos mediante modelos de lenguaje

## Descripción

El proyecto consiste en desarrollar un sistema capaz de generar informes
clínicos sintéticos de pacientes de Oncología Radioterápica mediante modelos
de lenguaje. Los informes simularán casos clínicos realistas de pacientes
adultos con cáncer de cabeza y cuello, incluyendo información como antecedentes,
pruebas diagnósticas, diagnóstico, tratamiento y evolución.

El objetivo es disponer de datos clínicos ficticios pero coherentes que puedan
utilizarse en tareas de experimentación y evaluación sin emplear información
real de pacientes.

## Motivación

Los datos médicos reales contienen información sensible y su uso está sujeto a importantes restricciones de privacidad y acceso. Además, en muchos casos no existe una cantidad suficiente de datos disponibles para trabajar de forma adecuada y los informes reales presentan una gran falta de homogeneidad, ya que pueden estar redactados con estructuras, niveles de detalle y formatos muy diferentes entre sí.
La generación de informes clínicos sintéticos permite disponer de un conjunto de ejemplos más amplio, controlado y uniforme, sin utilizar información personal de pacientes. Con este proyecto queremos estudiar hasta qué punto los modelos de lenguaje pueden generar informes clínicos variados, coherentes y con una estructura similar a la utilizada en un entorno hospitalario, además de analizar los errores que aparecen en las generaciones y mejorar progresivamente la calidad de los resultados.

## Alcance


### Incluido

El proyecto incluirá:

- Generación de informes clínicos sintéticos mediante modelos de lenguaje.
- Generación de casos de pacientes adultos de Oncología Radioterápica.
- Casos relacionados con cáncer de cabeza y cuello.
- Inclusión de antecedentes, pruebas diagnósticas, diagnóstico, tratamiento
  y evolución.
- Generación de pacientes y casos diferentes entre ejecuciones.
- Validación de la estructura y coherencia básica de los informes generados.
- Evaluación de los errores presentes en las generaciones.
### Fuera de alcance

Queda fuera del alcance del proyecto:

- El uso de datos clínicos reales identificables de pacientes.
- La utilización del sistema para realizar diagnósticos médicos reales.
- La sustitución de profesionales sanitarios.
- La generación de informes para pacientes reales.
- El entrenamiento desde cero de un modelo de lenguaje.
- La integración directa con los sistemas clínicos del hospital.
- 
## Funcionalidades

El sistema se divide inicialmente en las siguientes funcionalidades:

1. **Generación de informes clínicos sintéticos:** permite generar un nuevo
   caso clínico siguiendo unas condiciones y una estructura previamente
   definidas.

2. **Validación de los informes generados:** comprueba que el informe contiene
   las secciones necesarias y que cumple las principales restricciones
   establecidas para los casos clínicos.

3. **Evaluación de las generaciones:** permite analizar los informes obtenidos
   e identificar errores o problemas recurrentes en las respuestas de los
   modelos.

La definición detallada de cada funcionalidad se encuentra en la carpeta
`specs/`.

## Equipo

| Miembro | Rol | Contacto |
|---|---|---|
| María Mira Calvete | Desarrollo y evaluación | maria.mira.calvete@rai.usc.es |
| María de Miguel Fernández | Desarrollo y evaluación | maria.de.miguel@rai.usc.es |
| Claudia Mein García | Desarrollo y evaluación | claudia.mein@rai.usc.es |
## Estructura del repositorio

La documentación de esta entrega se organiza de la siguiente forma:

cu-18-informes-sinteticos/
├── README.md
└── specs/
    ├── generar-informe-prompts.md
    └── generar-informe-promptsyejemplos.md
    └── generar-informe-2fases.md
    └── validar-informe-clinico.md
    
