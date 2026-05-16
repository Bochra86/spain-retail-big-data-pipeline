# Spain Retail Big Data Pipeline with PySpark

# Pipeline de Big Data para Retail de España con PySpark

---

## English Version

## Project Overview

End-to-end Big Data analytics pipeline built with Apache PySpark for retail transaction analysis focused on the Spain market.

This project demonstrates real-world Data Engineering and Analytics Engineering concepts including ETL processing, large-scale data cleaning, feature engineering, star schema modeling, KPI generation, RFM customer segmentation, Spark optimization techniques, and parquet export.

The pipeline was developed using PySpark in Google Colab and simulates a production-style retail analytics workflow.

---

## Technologies Used

- Python
- PySpark
- Spark SQL
- DataFrames API
- Window Functions
- Parquet
- Google Colab

---

## Main Features

### Data Engineering
- Manual schema definition
- ETL pipeline design
- Data quality validation
- Duplicate removal
- Null value handling
- Business rule filtering
- Feature engineering
- Aggregations and transformations

### Data Modeling
- Star schema architecture
- Fact and dimension tables
- Surrogate key generation
- Analytical data marts

### Analytics & Business Intelligence
- Monthly revenue trend analysis
- Top-selling products
- Country-level sales analysis
- Customer purchasing behavior
- RFM customer segmentation
- KPI generation

### Performance Optimization
- Broadcast joins
- Adaptive Query Execution (AQE)
- Partitioned parquet storage
- Distributed processing with Spark

---

## Dataset

**Online Retail Dataset**  
Source: UCI Machine Learning Repository

Dataset contains:
- Customer transactions
- Product purchases
- Invoice information
- International retail sales
- Product quantities and prices
- Transaction timestamps

---

## Pipeline Architecture

```text
CSV Dataset
    ↓
PySpark ETL
    ↓
Data Cleaning
    ↓
Feature Engineering
    ↓
Star Schema Modeling
    ↓
KPI Analytics
    ↓
RFM Segmentation
    ↓
Parquet Export
```

---

## Project Structure

```text
├── images/
├── spain_retail_big_data_pipeline.ipynb
├── requirements.txt
└── README.md
```

---

## Output Files

The pipeline exports parquet datasets including:

- Fact Transactions
- Customer Dimension
- Product Dimension
- RFM Segments

Example parquet structure:

```text
spain_retail_parquet/
├── dim_customers/
├── dim_products/
├── fact_transactions/
└── rfm_segments/
```

---

## Sample KPIs

- Monthly Revenue Growth
- Active Customers
- Top Products by Revenue
- Customer Segmentation
- Average Basket Size
- Revenue by Country

---

## Screenshots

### Parquet Folder Structure

![Parquet Structure](images/parquet_folder_structure.png)

### Dataset Schema

![Data Schema](images/data_schema.png)

### Parquet Data Preview

![Parquet Preview](images/parquet_preview.png)

---

## How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Open the notebook:

```bash
spain_retail_big_data_pipeline.ipynb
```

3. Run all notebook cells sequentially.

---

## Future Improvements

- Delta Lake integration
- Airflow orchestration
- Real-time streaming with Spark Streaming
- Dashboard visualization with Power BI
- Deployment on AWS or Azure

---

## Author

Developed as a Big Data & PySpark portfolio project.

---

# Versión en Español

## Descripción del Proyecto

Pipeline completo de Big Data desarrollado con Apache PySpark para el análisis de transacciones retail enfocado en el mercado español.

El proyecto demuestra conceptos reales de Ingeniería de Datos y Analítica incluyendo procesamiento ETL, limpieza de grandes volúmenes de datos, feature engineering, modelado estrella, generación de KPIs, segmentación RFM, optimización de Spark y exportación en formato parquet.

El pipeline fue desarrollado utilizando PySpark en Google Colab simulando un flujo de trabajo real de analítica retail.

---

## Tecnologías Utilizadas

- Python
- PySpark
- Spark SQL
- API DataFrames
- Funciones Window
- Parquet
- Google Colab

---

## Características Principales

### Ingeniería de Datos
- Definición manual de schema
- Diseño de pipeline ETL
- Validación de calidad de datos
- Eliminación de duplicados
- Manejo de valores nulos
- Reglas de negocio
- Feature engineering
- Transformaciones y agregaciones

### Modelado de Datos
- Arquitectura Star Schema
- Tablas fact y dimensión
- Generación de surrogate keys
- Data marts analíticos

### Analítica & Business Intelligence
- Tendencia mensual de ingresos
- Productos más vendidos
- Análisis de ventas por país
- Comportamiento de clientes
- Segmentación RFM
- Generación de KPIs

### Optimización
- Broadcast joins
- Adaptive Query Execution (AQE)
- Almacenamiento parquet particionado
- Procesamiento distribuido con Spark

---

## Dataset

**Online Retail Dataset**  
Fuente: UCI Machine Learning Repository

El dataset contiene:
- Transacciones de clientes
- Compras de productos
- Información de facturas
- Ventas internacionales retail
- Cantidades y precios
- Fechas de transacciones

---

## Arquitectura del Pipeline

```text
CSV Dataset
    ↓
PySpark ETL
    ↓
Limpieza de Datos
    ↓
Feature Engineering
    ↓
Modelo Estrella
    ↓
KPIs
    ↓
Segmentación RFM
    ↓
Exportación Parquet
```

---

## Estructura del Proyecto

```text
├── images/
├── spain_retail_big_data_pipeline.ipynb
├── requirements.txt
└── README.md
```

---

## Archivos de Salida

El pipeline exporta datasets parquet incluyendo:

- Fact Transactions
- Customer Dimension
- Product Dimension
- RFM Segments

---

## Capturas de Pantalla

### Estructura de Carpetas Parquet

![Parquet Structure](images/parquet_folder_structure.png)

### Schema del Dataset

![Data Schema](images/data_schema.png)

### Vista Previa de Datos Parquet

![Parquet Preview](images/parquet_preview.png)

---

## Cómo Ejecutar

1. Instalar dependencias:

```bash
pip install -r requirements.txt
```

2. Abrir el notebook:

```bash
spain_retail_big_data_pipeline.ipynb
```

3. Ejecutar todas las celdas secuencialmente.

---

## Mejoras Futuras

- Integración con Delta Lake
- Orquestación con Airflow
- Streaming en tiempo real
- Dashboards con Power BI
- Deploy en AWS o Azure

---

## Autor

Proyecto desarrollado como portfolio de Big Data y PySpark.