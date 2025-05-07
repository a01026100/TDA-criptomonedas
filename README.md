# TDA-criptomonedas

## 📄 Descripción

Este notebook explora la **Problemática 1**: aplicar Topological Data Analysis (TDA) a series de precios históricos de criptomonedas. Se extraen componentes y ciclos mediante Mapper y homología persistente para identificar patrones de comportamiento de mercado.

## 📁 Estructura del repositorio

```bash
.
├── data/                       # CSV con precios históricos de criptomonedas
│   └── crypto_prices.csv
├── notebooks/                  # Notebooks organizados por etapas
│   └── Examen_A01026100.ipynb  # Notebook principal
├── requirements.txt            # Dependencias Python
└── README.md                   # Este archivo
```

## 🚀 Uso

1. Abre el notebook en Jupyter o Google Colab:

   ```bash
   jupyter lab notebooks/Examen_A01026100.ipynb
   ```
2. Ejecuta celdas en orden: Planteamiento, Metodología, Resultados y Conclusiones.

## 🧭 Estructura del Notebook

1. **Planteamiento del Problema**: descripción y contexto.
2. **Metodología**:

   * Carga y limpieza de datos
   * Ajuste de variables y creación de nuevas
   * Selección de lentes: UMAP para reducción de dimensionalidad y filtro de densidad para identificar regiones de alta concentración en el espacio de los datos
   * Construcción de grafo de Mapper: segmenta el espacio proyectado en intervalos solapados, agrupa puntos similares y conecta nodos que comparten datos para revelar la forma topológica
  
3. **Resultados y Análisis**
4. **Conclusiones**
5. **Referencias**

## 📸 Capturas de Pantalla

Estructura de la base de datos

<img width="635" alt="image" src="https://github.com/user-attachments/assets/7826e74c-fb5a-4c0f-b501-903ced8f272b" />

Lente con Densidad Y UMAP
<img width="507" alt="image" src="https://github.com/user-attachments/assets/f2645800-3b8c-4675-9eed-d62bef68589f" />

<img width="496" alt="image" src="https://github.com/user-attachments/assets/59aebe2a-23cc-4908-8b3b-36233750a294" />

Aplicación de Mapper
<img width="642" alt="image" src="https://github.com/user-attachments/assets/a8159edb-25bd-432d-a547-6c7857157b73" />

Grafo de Mapper
<img width="750" alt="image" src="https://github.com/user-attachments/assets/9048d3c6-d33e-40e1-a737-64b1504064ef" />


## 📈 Resultados Clave

* Identificación de ciclos estables en momentos de alta volatilidad.
* Detección de clusters de días con comportamiento similar.
* Mercado alcista separado en una sola componente

