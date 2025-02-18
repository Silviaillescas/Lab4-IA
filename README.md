# Lab4-IA
Michelle Mejía 22596 - Silvia Illescas 22376

## Segmentación de Clientes: GMM vs K-Means

### Descripción
Este proyecto implementa la segmentación de clientes utilizando dos enfoques principales:
1. Implementación manual de Gaussian Mixture Model (GMM).
2. Comparación con K-Means.

Se analiza un conjunto de datos de transacciones bancarias y se busca agrupar clientes según su comportamiento financiero.

### Estructura del Proyecto
- `Task2.py`: Codigo de los scripts realizados.
- `.csv`: Resultados de las segmentaciones corridas.
- `bank_transactions.csv`: Dataset original con información de clientes.

### Ejecución del Código
1. Instalar dependencias si no están instaladas:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
2. Ejecutar el script de segmentación:


### Metodología
#### 1. Carga y Preprocesamiento del Dataset
- Se manejan valores nulos con la mediana.
- Se escalan las variables para mejor rendimiento.

#### 2. Implementación Manual de GMM
- Se inicializan los centroides, matrices de covarianza y pesos.
- Se iteran los pasos Expectation (E-Step) y Maximization (M-Step) hasta convergencia.
- Se selecciona el número óptimo de clusters con log-verosimilitud.

#### 3. Visualización de Resultados
- Se usa PCA para reducir la dimensionalidad.
- Se grafican los clusters obtenidos.


