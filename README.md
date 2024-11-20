# Proyecto de Data Science: Optimización Comercial para Entidad Financiera

Este repositorio contiene un proyecto donde se aplicaron técnicas avanzadas de ciencia de datos para optimizar la estrategia comercial de la entidad financiera **easyMoney**, una fintech en crecimiento (simulación para el TFM). Este proyecto aborda tres áreas clave: la creación de un cuadro de mando en Power BI, el desarrollo de modelos de propensión a compra y la segmentación de clientes para definir buyer personas.

---

## Estructura del Repositorio

### Archivos principales al abrir el repositorio:
- **`EDA_Preprocesado_y_construccion_tablas.ipynb`**: Notebook principal para el análisis exploratorio, preprocesamiento y creación de tablas.
- **`Explicacion_profunda_caso_ToDo.pdf`**: Explicación del caso práctico con detalles sobre las tareas a resolver.
- **`Memoria_proyecto_final.pdf`**: Documento con los detalles y metodología del proyecto.

### Carpetas organizadas por tareas:
1. **`modelo_clustering_segmentacion_clientes/`**
   - `Buyer Persona Clusters.pdf`: Perfil detallado de los clusters creados.
   - `CLUSTERING_segmentacion_clientes.ipynb`: Notebook con el análisis de clustering y creación de segmentos.

2. **`modelos_propension_a_compra/`**
   - `modelo_PROPENSION_A_COMPRA_debit_card.ipynb`: Notebook para el modelo de propensión de tarjeta de débito.
   - `modelo_PROPENSION_A_COMPRA_long_term_deposit.ipynb`: Modelo de propensión para depósitos a largo plazo.
   - `modelo_PROPENSION_A_COMPRA_pension_plan.ipynb`: Modelo de propensión para planes de pensiones.

3. **`raw_datasets_y_diccionario_tablas/`**
   - Contiene los datasets originales y el diccionario de variables:
     - `customer_commercial_activity.xlsx`
     - `customer_products.xlsx`
     - `customer_sociodemographics.xlsx`
     - `diccionario_tablas.xlsx`
     - `product_description.xlsx`
     - `sales.xlsx`

---

## Requisitos

Asegúrate de tener instalados los siguientes paquetes:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `xgboost`
- `lightgbm`
- `catboost`
- `powerbi-client`

---

## Cómo Ejecutar el Proyecto

### 1. Clonar el Repositorio
Ejecuta los siguientes comandos en tu terminal para clonar el repositorio y acceder al directorio:
```bash
git clone https://github.com/tu_usuario/nombre_repositorio.git
cd nombre_repositorio
```

### 2. Ejecutar los Notebooks

- **Análisis Exploratorio y Construcción de Tablas**:  
  Abre y ejecuta el notebook `EDA_Preprocesado_y_construccion_tablas.ipynb` para:
  - Realizar un análisis exploratorio de los datos.
  - Preprocesar las tablas base.
  - Generar los datos necesarios para las siguientes etapas del proyecto.

- **Modelos de Propensión a Compra**:  
  Accede a la carpeta `modelos_propension_a_compra/` y ejecuta los siguientes notebooks para generar y evaluar los modelos predictivos:
  - `modelo_PROPENSION_A_COMPRA_debit_card.ipynb`: Modelo para tarjetas de débito.
  - `modelo_PROPENSION_A_COMPRA_long_term_deposit.ipynb`: Modelo para depósitos a largo plazo.
  - `modelo_PROPENSION_A_COMPRA_pension_plan.ipynb`: Modelo para planes de pensiones.

- **Clustering y Segmentación**:  
  Ve a la carpeta `modelo_clustering_segmentacion_clientes/` y ejecuta el notebook:
  - `CLUSTERING_segmentacion_clientes.ipynb`: Realiza la segmentación de clientes utilizando técnicas de clustering y genera perfiles de buyer persona.

### 3. Explorar el Dashboard

- **Power BI Dashboard**:  
  Abre el archivo del dashboard en **Power BI Desktop** para:
  - Visualizar las tendencias de ventas y KPI clave.
  - Realizar análisis interactivos basados en los datos procesados.

### 4. Revisar la Documentación

- Consulta los siguientes documentos en formato PDF para obtener detalles adicionales sobre el proyecto:
  - `Explicacion_profunda_caso_ToDo.pdf`: Detalla las tareas y el enfoque del proyecto.
  - `Memoria_proyecto_final.pdf`: Explica la metodología, resultados y conclusiones del trabajo.

---

## Resultados Clave

### Dashboard en Power BI

Un dashboard interactivo que proporciona:
- Visualizaciones de ventas, KPI y tendencias clave.
- Análisis detallado para facilitar la toma de decisiones.

### Modelos de Propensión a Compra

Se desarrollaron modelos predictivos que identifican los clientes más propensos a adquirir:
- **Tarjeta de débito**
- **Plan de pensiones**
- **Depósitos a largo plazo**

### Segmentación de Clientes

Segmentación de clientes en **7 clusters** basados en análisis de datos, cada uno con un perfil detallado de buyer persona. Esto permite:
- Personalizar estrategias de marketing.
- Aumentar la rentabilidad enfocándose en segmentos específicos.

---

¡Explora este proyecto y descubre cómo los datos pueden transformar estrategias comerciales en el sector financiero!
