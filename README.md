# Evaluación Final - Módulo 3: Data Analytics

## 📋 Descripción del Proyecto

Este proyecto corresponde al **Ejercicio de Evaluación Final del Módulo 3** del Bootcamp de Análisis de Datos de **Adalab**.

**Alumna:** Leire Marinas

---

## 🎯 Objetivo

Analizar el comportamiento de los clientes dentro de un programa de lealtad de una aerolínea mediante exploración de datos, limpieza, análisis estadístico y visualización.

---

## 📊 Datasets Utilizados

1. **Customer_Flight_Activity.csv**: Información sobre la actividad de vuelo de los clientes
2. **Customer_Loyalty_History.csv**: Perfil detallado de los clientes del programa de lealtad

---

## 🔍 Fases del Proyecto

### Fase 1: Exploración y Limpieza
- Exploración inicial de los datos
- Identificación y tratamiento de valores nulos
- Unión eficiente de los dos datasets mediante `merge`
- Verificación de duplicados

### Fase 2: Análisis Estadístico
- Estadísticas descriptivas de variables numéricas
- Identificación de valores atípicos (outliers) mediante método IQR
- Análisis de correlación entre variables numéricas
- Distribución de frecuencias de variables categóricas

### Fase 3: Visualización
Se respondieron 6 preguntas clave mediante gráficos:
1. Distribución de vuelos reservados por mes
2. Relación entre distancia y puntos acumulados
3. Distribución de clientes por provincia
4. Comparación de salario por nivel educativo
5. Proporción de tipos de tarjetas de fidelidad
6. Distribución por estado civil y género

### Fase 4: Evaluación Estadística
- Análisis de diferencias en reservas de vuelos según nivel educativo
- Estadísticas descriptivas por grupo educativo

---

## 🛠️ Herramientas y Librerías

- **Python 3**
- **Pandas**: Manipulación y análisis de datos
- **NumPy**: Operaciones numéricas
- **Matplotlib**: Visualización de datos
- **Seaborn**: Visualización estadística avanzada

---

## 📈 Principales Conclusiones

- El programa de lealtad otorga puntos de manera proporcional a la distancia volada
- Existe un patrón estacional claro: más reservas en verano y navidad
- El nivel educativo NO influye significativamente en el número de vuelos reservados
- La base de clientes está equilibrada en género
- Los clientes casados representan el segmento más grande

---

## 📁 Estructura del Proyecto
```
├── Documentación/
│   ├── Customer_Flight_Activity.csv
│   ├── Customer_Loyalty_History.csv
│   └── evaluacion-final.pdf
├── Evaluación_Modulo3_Leire.ipynb
└── README.md
```

---

## 👩‍💻 Autora

**Leire Marinas**  
Bootcamp de Análisis de Datos - Adalab  
Módulo 3: Data Analytics  
Enero 2026