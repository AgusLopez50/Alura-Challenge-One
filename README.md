📊 Alura Store — Análisis de Ventas y Rendimiento
📌 Propósito
Este proyecto analiza datos de ventas, reseñas y costos de envío de las 4 tiendas de la cadena Alura Store con el objetivo de ayudar al Sr. Juan a decidir qué tienda vender para financiar un nuevo emprendimiento.

Se utilizan métricas clave y visualizaciones para identificar la tienda menos eficiente, respaldando la decisión con datos.

🗂 Estructura del proyecto
bash
Copiar
Editar
.
├── Alura_Store_Analisis.ipynb   # Notebook principal con todo el análisis
├── Alura_Store_Reporte.md       # Informe ejecutivo con la recomendación final
├── data/                        # Carpeta para los archivos CSV de las tiendas
└── README.md                    # Documentación del proyecto
📊 Ejemplos de gráficos e insights
1️⃣ Facturación total por tienda
Gráfico de barras y circular mostrando el total de ingresos por cada tienda.

matlab
Copiar
Editar
Tienda A — 40% de la facturación total  
Tienda B — 25%  
Tienda C — 20%  
Tienda D — 15%
2️⃣ Categorías más vendidas
Barras con el Top 5 de categorías por unidades vendidas en cada tienda.

3️⃣ Relación entre costo de envío y valor del pedido
Gráfico de dispersión que revela si costos altos de envío afectan pedidos de bajo valor.

4️⃣ Histograma de reseñas
Distribución de calificaciones para evaluar satisfacción del cliente.

🚀 Instrucciones para ejecutar el notebook
1. Clonar este repositorio
bash
Copiar
Editar
git clone https://github.com/usuario/alura-store-analisis.git
cd alura-store-analisis
2. Preparar los datos
Colocar los archivos CSV de cada tienda en la carpeta data/
(o definir la ruta de un único CSV consolidado en la variable SINGLE_CSV dentro del notebook).

3. Instalar dependencias
bash
Copiar
Editar
pip install pandas matplotlib
4. Ejecutar el notebook
Opción 1: Jupyter Notebook

bash
Copiar
Editar
jupyter notebook Alura_Store_Analisis.ipynb
Opción 2: Google Colab

Subir el archivo .ipynb a Google Colab

Montar Google Drive si los datos están allí.

5. Revisar resultados
Las métricas y gráficos se encuentran organizados por secciones.

El informe final (Alura_Store_Reporte.md) indica la tienda recomendada para vender.

📈 Principales insights obtenidos (ejemplo)
Tienda D presenta la menor facturación y altos costos de envío.

Tienda B tiene buena facturación pero baja calificación promedio.

La categoría “Electrónica” domina en Tienda A y C, mientras que Tienda D depende de productos de baja rotación.

📄 Licencia
Este proyecto se distribuye bajo la licencia MIT.

