Markdown# Introducción a Ciencia de Datos 📊

Este repositorio contiene materiales, ejercicios y bases de datos desarrollados durante el curso de **Introducción a Ciencia de Datos**. Aquí se documenta el progreso en el aprendizaje de herramientas para análisis estadístico y manipulación de datos con un enfoque en **Ingeniería Financiera**.

---

## 📁 Estructura del Repositorio

A continuación se detallan los materiales disponibles en este repositorio:

```text
Introduccion-Ciencia-de-Datos/
│
├── 📂 Clase 4/                  # Notebooks y ejercicios de la Sesión 4
├── 📂 Clase 5/                  # Estadística descriptiva y Boxplots
├── 📂 Clase Numpy/              # Fundamentos de computación numérica
├── 📂 Clase_6/                  # Casos prácticos avanzados
├── 📓 Ejercicio_Ciencia_de_Datos.ipynb  # Consolidado de ejercicios prácticos
├── 📄 customers_1.csv           # Dataset principal: Segmentación de clientes
└── 📄 default of credit card... # Dataset: Análisis de riesgo crediticio
🗂️ Contenidos del Curso1. Análisis Exploratorio y EstadísticaSe profundiza en la anatomía de los datos y la identificación de valores atípicos (outliers).Fórmulas aplicadas ($LaTeX$):$$IQR = Q_3 - Q_1$$$$\text{Valla Superior} = Q_3 + (1.5 \times IQR)$$Snippet - Agregación de datos con Pandas:Python# Resumen estadístico agrupado por ocupación
resumen = df.groupby('Occupation')['Income'].agg(['mean', 'median', 'std'])
print(resumen)
2. Visualización EstadísticaUso de Matplotlib y Seaborn para entender la distribución de variables financieras.Histogramas: Frecuencia de ingresos y salarios.Boxplots: Análisis comparativo de la dispersión de datos por categorías.3. Computación con NumPyManejo de estructuras de datos eficientes para cálculos a gran escala.Aplicación: Generación de datos sintéticos y transformaciones matriciales.📊 Variables del Dataset (customers_1.csv)VariableTipoDescripciónCustomerIDint64Identificador único del clienteAgeint64Edad (años)Incomeint64Ingreso anual estimadoOccupationobjectTipo de empleo (Official, Unemployed, etc.)Settlement SizeobjectTamaño de la ciudad de residencia🛠️ Stack TecnológicoLenguaje: Python 3.xLibrerías: Pandas, NumPy, Matplotlib, Seaborn.Entornos: Jupyter Notebook / Google Colab.🧠 Habilidades DemostradasAnálisis Cuantitativo: Interpretación de métricas estadísticas aplicadas a finanzas.Limpieza de Datos: Manejo de valores faltantes y tipado de datos con Pandas.Documentación Científica: Uso de Markdown y notación matemática en reportes técnicos.👤 AutorNicoll Tatiana Rios Sepulveda Estudiante de Ingeniería Financiera / Ciencia de Datos[!NOTE]Este repositorio es de carácter académico y se actualiza conforme al progreso del curso.
