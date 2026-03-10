# Análisis de Evasión de Clientes (Churn) – Telecom X

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el fenómeno de evasión de clientes (Churn) en la empresa Telecom X. La evasión de clientes ocurre cuando un usuario decide cancelar el servicio contratado, lo que representa una pérdida importante para la empresa.

A través de técnicas de análisis de datos se busca identificar patrones y factores asociados al abandono de clientes, con el fin de generar insights que permitan mejorar las estrategias de retención.

El análisis se realizó utilizando Python en un entorno de Google Colab, aplicando procesos de limpieza, transformación y exploración de datos.

---

## Objetivos del Análisis

- Analizar la distribución de clientes que abandonan el servicio.
- Identificar variables que influyen en el churn.
- Explorar patrones relacionados con el tipo de contrato, cargos y servicios contratados.
- Proponer recomendaciones estratégicas para reducir la evasión de clientes.

---

## Tecnologías Utilizadas

- Python
- Pandas
- Matplotlib
- Google Colab

---

## Proceso del Proyecto

El análisis se desarrolló en las siguientes etapas:

### 1. Extracción de Datos
Los datos fueron obtenidos desde una API en formato JSON y posteriormente cargados en un DataFrame de Pandas para su manipulación.

### 2. Limpieza y Transformación de Datos
Durante esta etapa se realizaron las siguientes tareas:

- Normalización de estructuras JSON.
- Identificación y tratamiento de valores nulos.
- Conversión de variables categóricas binarias (Yes/No) a valores numéricos (1/0).
- Estandarización de nombres de columnas.
- Conversión de variables numéricas almacenadas como texto.

También se creó una nueva variable llamada **Cuentas_Diarias**, calculada a partir del cargo mensual del cliente.

### 3. Análisis Exploratorio de Datos (EDA)

Se realizaron diferentes análisis y visualizaciones para comprender mejor el comportamiento de los clientes, incluyendo:

- Distribución de la variable Churn.
- Análisis de churn según tipo de contrato.
- Análisis de churn según método de pago.
- Comparación de cargos mensuales entre clientes que permanecen y los que abandonan.

---

## Principales Hallazgos

A partir del análisis se identificaron varios patrones importantes:

- Los clientes con contratos **mensuales** presentan una mayor tasa de abandono.
- Los clientes con **menor tiempo en la empresa** tienen mayor probabilidad de cancelar el servicio.
- Algunos clientes con **cargos mensuales más altos** muestran mayor tendencia a abandonar.
- La contratación de **servicios adicionales** parece estar asociada con una mayor permanencia.

---

## Recomendaciones

Basado en los resultados del análisis se proponen las siguientes acciones:

- Incentivar contratos de mayor duración mediante promociones o descuentos.
- Implementar estrategias de fidelización para clientes nuevos.
- Promover servicios adicionales que aumenten el valor percibido por el cliente.
- Analizar la estructura de precios para identificar oportunidades de mejora.

---

## Autor

Proyecto desarrollado por Luis Fernando Mamani Mamani como parte del desafío de análisis de datos de Alura Latam.
