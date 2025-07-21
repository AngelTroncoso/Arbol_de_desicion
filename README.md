# 🌳 Predicción de Precios de Viviendas con Árboles de Decisión 🏠
![vivienda](https://image.lexica.art/full_webp/108ff282-e79c-43f8-9a39-840cefa68fc9)

¡Bienvenido al repositorio de modelos predictivos para bienes raíces! Este proyecto utiliza **Árboles de Decisión para Regresión** para estimar el valor de propiedades basado en sus características. Ideal para inmobiliarias, inversores y compradores inteligentes.

## 📋 Tabla de Contenidos
1. [Requisitos](#🔧-requisitos)
2. [Instalación](#⚙️-instalación)
3. [Uso](#🚀-uso)
4. [Estructura del Proyecto](#📂-estructura-del-proyecto)
5. [Datos](#📊-datos)
6. [Resultados](#📈-resultados)
7. [Contribución](#🤝-contribución)
8. [Licencia](#📜-licencia)
9. [Contacto](#📧-contacto)

---

## 🔧 Requisitos
- Python 3.8+
- Bibliotecas: `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `graphviz`
- Memoria RAM: 4GB+ (para visualización de árboles grandes)

## ⚙️ Instalación
```bash
# Clonar repositorio
git clone https://github.com/tuusuario/arboles-precios-viviendas.git

# Instalar dependencias
pip install -r requirements.txt
```
## 📂 Estructura del Proyecto  

├── data/  
│   ├── viviendas.csv                # Dataset de propiedades  
│   └── generador_datos.py           # Script para generar datos ficticios  
├── modelos/  
│   ├── entrenamiento_arbol.py       # Entrenamiento del árbol  
│   ├── optimizacion_hiperparametros.py  # Búsqueda de mejor configuración  
│   └── evaluacion.py                # Métricas de desempeño  
├── notebooks/  
│   ├── exploracion_datos.ipynb      # Análisis exploratorio  
│   └── interpretacion_arbol.ipynb   # Explicabilidad del modelo  
├── resultados/  
│   ├── arbol_decision.png           # Visualización del árbol  
│   ├── importancia_variables.png    # Gráfico de importancia  
│   └── metricas.txt                 # Resultados numéricos  
└── requirements.txt  

## 📊 Datos  

- Variables del dataset ficticio (generado sintéticamente):

- habitaciones (Número de habitaciones, 1-6)

- banos (Número de baños completos, 1-4)

- tamano_m2 (Tamaño en metros cuadrados, 50-300)

- jardin (Presencia de jardín: Si/No)

- antiguedad (Años desde construcción, 1-50)

- ubicacion (Zona: Centro/Norte/Sur/Este/Oeste)

- Target: precio (Valor en miles de USD)

## 🤝 Contribución  
¡Contribuciones son bienvenidas! Sigue estos pasos:

- Reporta bugs o mejoras en Issues

- Haz fork del proyecto

- Crea tu rama: git checkout -b feature/nueva-caracteristica

- Realiza tus cambios: git commit -m 'Mejora en visualización'

- Haz push: git push origin feature/nueva-caracteristica

- Abre un Pull Request
  
## 📜 Licencia
Distribuido bajo licencia MIT. Ver LICENSE para más información.

¡Si te gusto, Dejame una estrella ! 🌟
