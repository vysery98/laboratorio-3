## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías principales:**
    * `Pandas`: Para manipulación de estructuras de datos.
    * `NumPy`: Para operaciones matriciales.
    * `Matplotlib` & `Seaborn`: Para la creación de gráficos estadísticos y temas visuales.

## 🚀 Flujo de Trabajo
1. **Carga e Inspección:** Se verifica la integridad de los datos (no se encontraron valores nulos).
2. **Limpieza de Datos:** Se eliminaron las columnas `RowNumber`, `CustomerId` y `Surname`, ya que no aportan valor estadístico para la predicción.
3. **Análisis de la Variable Objetivo:** Se determinó que el **20.38%** de los clientes en el dataset han desertado (`Exited = 1`).
4. **Visualización:** Análisis de distribuciones generales de los clientes.

## 📸 Evidencias (Resultados del Análisis)

### Distribución de la Deserción
![Gráfico de Churn](./screenshots/Imagen1.png)

### Correlación de Variables
![Heatmap de Variables](./screenshots/Imagen2.png)

### 6 Análisis de deserción por segmentos:
![Heatmap de Variables](./screenshots/Imagen3.png)

### Visualización 7: Tasa de deserción por país
![Heatmap de Variables](./screenshots/Imagen4.png)

### Visualización 8: Deserción según actividad del cliente
![Heatmap de Variables](./screenshots/Imagen5.png)

### Visualización 9: Deserción por número de productos
![Heatmap de Variables](./screenshots/Imagen6.png)

### Visualización 10: Deserción por rango de edad
![Heatmap de Variables](./screenshots/Imagen7.png)


## 📂 Requisitos para Ejecutar
1. Tener instalado **Jupyter Notebook** o **VS Code**.
2. Instalar las librerías necesarias:
   ```bash
   pip install pandas numpy matplotlib seaborn
   