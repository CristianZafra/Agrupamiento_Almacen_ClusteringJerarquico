# Optimización del Almacenamiento con Agrupamiento Jerárquico Aglomerativo

Este repositorio contiene un cuaderno interactivo en **Colaboración de Google** que aplica un modelo de **agrupamiento jerárquico aglomerativo** para identificar patrones de similitud entre ítems en un almacén. Este infoque permite optimizar el diseño de mantenimiento con base en variables clave como **frecuencia de uso, volumen y peso**.

---

## Objetivo

- Agrupar ítems por similitud operativa y física.
- Visualizar agrupamentos mediantes dendrogramas y diagramas de dispersión.
- Decisiones facilitadoras para mejorar la distribución interna del mantenimiento (zonificación, rutas de selección, mantenimiento ABC).

---

## Requisitos de los datos

El archivo `datos_almacen_clustering.csv` debe contener las siguientes columnas:

- `Item_ID`: identificador del ítem
- `Frecuencia_uso`: número de veces que el ítem se usa o retira
- `Volumen`: volumen ocupado por el ítem (m³)
- `peso`: peso del ítem (kg)
- `Categoria`: (opcional) clasificación ABC previa

> Puedes usar el archivo de ejemplo:  
>  [datos_almacen_clustering.csv](https://github.com/CristianZafra/Agrupamiento_Almacen_ClusteringJerarquico/blob/main/datos_almacen_clustering.csv)

---

## ¿como usar este proyecto?

1. **Clona o descarga este repositorio.**

```bash
clon git https://github.com/tuusuario/Clustering_Almacen_HCA.git
