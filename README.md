# TP1 - Un primer encuentro con la EPH

**Taller de Programación (UBA, 2026). Grupo 8**
Estatus asignado: *Informal self-employed* (trabajadores independientes informales)

**Docente:** Noelia Romero
**Integrantes:** Mayra Lemes Lapasta y Javier Hernández Aldana

## Descripción

Análisis de la informalidad laboral entre trabajadores independientes, a partir de
los microdatos de la Encuesta Permanente de Hogares (EPH-INDEC), comparando el
4° trimestre de 2024 con el 4° trimestre de 2025. Incluye limpieza de datos,
análisis de valores faltantes, matriz de correlación, estadística descriptiva,
construcción de un indicador de informalidad siguiendo a Maurizio & Monsalvo (2021)
y análisis de la distribución del ingreso.

## Organización del repositorio

- `TP1_Programacion_Grupo8.ipynb` - notebook con todo el análisis (incisos 2 a 11).
- `bases/` - bases de datos (ver nota más abajo).
- `output/` - figuras generadas por el notebook.

## Cómo obtener las bases de datos

 **Las bases individuales de la EPH no se incluyen en el repositorio por su tamaño.**
Para reproducir el análisis, descargarlas del sitio del INDEC y colocarlas en `bases/`:

1. Ir a https://www.indec.gob.ar → *Servicios y herramientas → Bases de datos → Mercado laboral*. 
2. Descargar las bases **individuales** del 4° trimestre de 2024 y del 4° trimestre de 2025.
3. Colocar los archivos en `TP1/bases/` con los nombres:
   - `usu_individual_T424.xlsx`
   - `usu_individual_T425.xlsx`

El archivo `bases/ipc_nivel_general.xlsx` (IPC para deflactar) sí está incluido.

## Requisitos

- Python 
- Librerías: `pandas`, `numpy`, `matplotlib`, `seaborn`, `openpyxl`

## Cómo ejecutar

Abrir el notebook en Jupyter y ejecutar todas las celdas en orden
(*Kernel → Restart & Run All*). Requiere las bases en `TP1/bases/`.
