# Desafío ONE | Análisis de Datos para la Decisión de Venta (Alura Store)

##  1. Resumen del Proyecto

Este proyecto forma parte del desafío de análisis de datos de ONE (Oracle Next Education) e Immersión en Datos de Alura Latam.

El objetivo principal fue utilizar Python y sus bibliotecas de análisis (Pandas y Matplotlib/Folium) para **evaluar el rendimiento de cuatro tiendas de la cadena Alura Store**. El propósito era identificar la tienda menos eficiente y emitir una recomendación ejecutiva para el Sr. Juan sobre qué activo debería vender para financiar su nuevo emprendimiento.

**Conclusión Principal:** Se recomienda la venta de la **Tienda 4** debido a su bajo rendimiento financiero.

---

## 2. Análisis y Métricas Clave

Se realizaron cinco análisis fundamentales para comparar el rendimiento de las cuatro tiendas:

| Métrica Analizada | Resultado Clave | Conclusión |
| :--- | :--- | :--- |
| **Facturación Total** | Tienda 4 con el menor ingreso total. | Principal candidata a venta. |
| **Calificación Promedio** | Todas las tiendas tienen una calificación alta (~4.0). | La calidad/servicio **no** es el problema de la Tienda 4. |
| **Costo Promedio de Envío** | Tienda 4 con el costo logístico más bajo. | La ineficiencia **no** es logística. |
| **Análisis de Productos** | Tienda 4 falla en rotar productos clave de alto margen. | Problema de **mezcla de productos (product mix)**. |
| **Análisis Geográfico (Heatmap)** | Baja densidad de ventas fuera del nicho geográfico central de la Tienda 4. | Confirma la baja **penetración de mercado**. |

---

## 3. Herramientas y Dependencias

Las siguientes herramientas y librerías fueron utilizadas en el desarrollo de este análisis:

* **Python 3.x**
* **Jupyter/Google Colab:** Entorno de desarrollo para la ejecución del código.
* **Pandas:** Manipulación y estructuración de los datos.
* **Matplotlib:** Generación de gráficos comparativos (Barras, Eje Dual).
* **Folium:** Generación de Mapas Interactivos y Mapas de Calor (Heatmaps) para el análisis geográfico extra.

## 🚀 4. Estructura del Proyecto

El código fuente principal se encuentra en el cuaderno base proporcionado por Alura.

* `[Nombre de tu archivo].ipynb` o `Desafio_Alura_Store.ipynb`: Cuaderno de Jupyter/Colab que contiene todo el código de carga, limpieza, análisis, visualización y el informe final.
* `README.md`: Este archivo de documentación.
* *Otros archivos de soporte (ej. Imágenes generadas si las exportaste).*

### Cómo Ejecutar el Proyecto

1.  **Clonar el Repositorio:**
    ```bash
    git clone [https://docs.github.com/es/repositories/creating-and-managing-repositories/quickstart-for-repositories](https://docs.github.com/es/repositories/creating-and-managing-repositories/quickstart-for-repositories)
    ```
2.  **Abrir el Cuaderno:** Sube el archivo `.ipynb` a Google Colab o abrelo en tu entorno local (Jupyter Notebook/Lab).
3.  **Ejecutar las Celdas:** Ejecuta las celdas secuencialmente para replicar el análisis completo y visualizar el informe ejecutivo.

---

## 5. Contacto

 Gonzalo Galvan
(https://www.linkedin.com/in/gonzalo-ignacio-galvan/)
(https://github.com/G0ncho)

Para ejecutar el proyecto, asegúrate de tener instaladas las dependencias:
```bash
pip install pandas matplotlib folium numpy

---

