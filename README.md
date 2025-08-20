# Análisis de Evasión de Clientes - Telecom X

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.5.0+-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.6.0+-red.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12.0+-orange.svg)
![Google Colab](https://img.shields.io/badge/Google_Colab-Compatible-yellow.svg)

## Descripción del Proyecto

Este repositorio contiene el análisis completo del proyecto "Churn de Clientes" para Telecom X. El objetivo principal es identificar los factores que influyen en la evasión (churn) de clientes y proporcionar recomendaciones estratégicas basadas en datos para reducir esta tasa.

Telecom X enfrenta un desafío crítico con su alta tasa de cancelaciones, lo que afecta directamente a sus ingresos y crecimiento. Este proyecto aplica técnicas de análisis de datos para transformar datos brutos en información accionable que permita desarrollar estrategias efectivas de retención de clientes.

## Contexto del Negocio

Telecom X es una empresa de telecomunicaciones que ofrece diversos servicios como:
- Telefonía fija
- Internet
- Servicios de seguridad en línea
- Respaldos en la nube
- Protección de dispositivos
- Soporte técnico
- Streaming de TV y películas

La empresa ha identificado que la tasa de evasión de clientes representa un problema crítico para su sostenibilidad y crecimiento, por lo que ha comisionado este análisis para comprender las causas raíz y desarrollar estrategias efectivas de retención.


## Metodología

El análisis sigue la metodología ETL (Extracción, Transformación y Carga), complementada con un exhaustivo Análisis Exploratorio de Datos (EDA):

### 1. Extracción
- Conexión y extracción de datos desde la API de Telecom X
- Transformación del formato JSON a DataFrame de Pandas
- Verificación inicial de la estructura y calidad de los datos

### 2. Transformación
- Limpieza y estandarización de variables categóricas
- Tratamiento de valores inconsistentes
- Creación de nuevas variables derivadas (cuentas diarias, cantidad de servicios, categorías de antigüedad)
- Codificación de variables para análisis estadístico

### 3. Carga y Análisis
- Análisis descriptivo de los datos
- Visualizaciones de la distribución de churn
- Análisis de factores categóricos relacionados con el churn
- Análisis de variables numéricas y su relación con la evasión
- Estudio de correlaciones entre variables

### 4. Informe Final
- Síntesis de hallazgos clave
- Identificación de patrones y factores determinantes
- Desarrollo de recomendaciones estratégicas
- Propuesta de próximos pasos

## Principales Hallazgos

El análisis reveló varios factores determinantes en la decisión de los clientes de abandonar los servicios:

1. **Tipo de contrato**: Los clientes con contrato mensual presentan una tasa de evasión 6 veces mayor que aquellos con contratos de dos años.

2. **Servicios de seguridad y soporte**: Los clientes sin servicios como seguridad en línea o soporte técnico tienen aproximadamente el doble de probabilidad de cancelar.

3. **Antigüedad del cliente**: El primer año es el período más crítico para la retención, con una tasa de evasión significativamente mayor.

4. **Método de pago**: Los clientes que pagan con cheque electrónico muestran una mayor tendencia a la evasión en comparación con métodos automáticos.

5. **Cantidad de servicios**: Existe un "punto óptimo" de 4-5 servicios contratados que minimiza la probabilidad de evasión.

## Recomendaciones Estratégicas

Basado en los hallazgos, se proponen las siguientes estrategias para reducir la tasa de evasión:

1. **Incentivos para contratos a largo plazo**:
   - Implementar descuentos o beneficios exclusivos para contratos de uno o dos años
   - Ofrecer período de prueba antes de solicitar compromiso a largo plazo

2. **Programa especial para nuevos clientes**:
   - Desarrollar un programa de atención personalizada durante los primeros 12 meses
   - Establecer puntos de contacto regulares para evaluar satisfacción

3. **Optimización de paquetes de servicios**:
   - Promocionar activamente el paquete de 4-5 servicios identificado como óptimo
   - Ofrecer servicios de seguridad y soporte técnico con descuento inicial

4. **Mejoras en sistema de pago y facturación**:
   - Incentivar la adopción de métodos de pago automáticos
   - Simplificar el proceso de facturación

5. **Sistema de alerta temprana**:
   - Desarrollar un modelo predictivo para identificar clientes con alto riesgo de evasión
   - Implementar intervenciones proactivas basadas en los factores identificados

## Tecnologías Utilizadas

- **Python 3.9+**: Lenguaje de programación principal
- **Pandas**: Manipulación y análisis de datos
- **NumPy**: Operaciones numéricas
- **Matplotlib y Seaborn**: Visualización de datos
- **Google Colab**: Entorno de desarrollo y ejecución

## Cómo Ejecutar el Análisis

1. Clone este repositorio:
   ```bash
   git clone https://github.com/JoseMartinez-AI/Proyecto-ETL-TelecomX.git
   cd Proyecto-ETL-TelecomX

## Autor
**Jose Martínez**