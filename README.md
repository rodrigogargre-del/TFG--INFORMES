# TFG – Evaluador inteligente en el Simulador de Navegación (SIMNAV)

Este repositorio reúne los materiales generados durante el desarrollo del Trabajo de Fin de Grado (TFG) centrado en el diseño e implementación de un sistema automático de evaluación de la seguridad en la navegación aplicado al simulador de navegación de la Escuela Naval Militar.

El proyecto propone un evaluador capaz de analizar ejercicios de navegación realizados en simulador a partir de los datos registrados durante el ejercicio. Mediante técnicas de análisis de datos, detección de eventos críticos y modelos de evaluación basados en lógica borrosa, el sistema genera informes automáticos que permiten valorar el nivel de seguridad de la navegación realizada.

El objetivo de este repositorio es mostrar tanto los **informes generados por el evaluador** como los **bloques de código desarrollados durante el proyecto**, así como algunos ejemplos representativos de análisis completos.

---

## Estructura del repositorio
```
TFG_EVALUADOR_NAVEGACION
│
├── INFORMES_SEGURIDAD_EN_LA_NAVEGACION
│   ├── FERROL
│   └── ROTA
│
├── CODIGOS_DESARROLLADOS
│   ├── FERROL
│   └── ROTA
│
└── EVALUACION_CONJUNTA
    ├── EJERCICIO_1_ROTA
    ├── EJERCICIO_2_ROTA
    ├── EJERCICIO_1_FERROL
    └── EJERCICIO_2_FERROL 
```    
---

## Informes de evaluación de seguridad

La carpeta **INFORMES_SEGURIDAD_EN_LA_NAVEGACION** contiene una colección de informes generados automáticamente por el sistema evaluador tras analizar ejercicios de navegación realizados en simulador.

Se incluyen:

- **5 ejercicios desarrollados en el entorno de Ferrol**
- **5 ejercicios desarrollados en el entorno de Rota**

Cada informe presenta el análisis completo del ejercicio e incluye:

- La trayectoria seguida durante la navegación  
- La evaluación de seguridad obtenida  
- Evidencias gráficas del encuentro entre buques  
- La interpretación automática del resultado  
- Recomendaciones orientadas a la mejora del ejercicio  

Estos documentos muestran ejemplos reales del tipo de retroalimentación que el sistema puede proporcionar a los alumnos tras finalizar un ejercicio de simulación.

---

## Códigos desarrollados

La carpeta **CODIGOS_DESARROLLADOS** reúne los principales bloques de código generados durante el desarrollo del proyecto.

Los scripts se organizan por entorno operativo (Ferrol y Rota) e incluyen, entre otros, los módulos destinados a:

- Procesamiento de los datos de navegación registrados en el simulador  
- Detección de eventos críticos entre buques  
- Evaluación de la seguridad en la navegación  
- Análisis de encuentros conforme al Reglamento Internacional para Prevenir los Abordajes (RIPA)  
- Generación automática de informes de evaluación  

---

## Evaluación conjunta de ejercicios

La carpeta **EVALUACION_CONJUNTA** incluye ejercicios representativos utilizados para mostrar el funcionamiento completo del sistema de evaluación.

En ella se presentan **cuatro ejercicios seleccionados**, dos correspondientes al entorno de Rota y dos al entorno de Ferrol, que permiten ilustrar diferentes situaciones de tráfico marítimo y distintos resultados del proceso de evaluación.

Cada ejercicio incluye el informe generado por el sistema junto con una explicación del análisis realizado.

---

## Contexto del proyecto

Este trabajo forma parte del desarrollo de un sistema de apoyo a la instrucción en navegación marítima dentro del simulador de navegación de la Escuela Naval Militar.

El evaluador desarrollado permite analizar automáticamente los ejercicios realizados por los alumnos, generando informes interpretativos que facilitan la comprensión de los resultados obtenidos y ayudan a identificar aspectos de mejora en la conducción del buque.

---

## Autor

AF Rodrigo García Gregori  
Trabajo de Fin de Grado  
Escuela Naval Militar
