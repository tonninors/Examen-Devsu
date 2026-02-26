# Prueba Técnica

Solución a la prueba técnica de **Data Engineer / Data Engineer Senior** desarrollada en Google Colab.

## Contenido

| Archivo | Descripción |
|---------|-------------|
| `Prueba_Técnica_DE_BP.ipynb` | Notebook principal con todas las respuestas |
| `resultados.zip` | Archivos de resultado generados por los scripts |

## Secciones del examen

### Sección 1 — SQL (SQLite)
Simulación de la primera ronda del **Mundial Qatar 2022**:
- Tablas: `Partidos`, `Clasificados`, `Resultados_Qatar`
- Preguntas sobre clasificación por grupo, diferencia de goles y cruces de octavos de final

### Sección 2 — PySpark
Procesamiento distribuido de datos con PySpark sobre los mismos datasets del Mundial.

## Tecnologías

- Python 3 · PySpark · SQLite
- Google Colab

## Cómo ejecutar

1. Abrir `Prueba_Técnica_DE_BP.ipynb` en [Google Colab](https://colab.research.google.com/)
2. Ejecutar la celda de configuración del ambiente (instala PySpark y SQLite)
3. Reiniciar el runtime cuando se solicite
4. Ejecutar las celdas de cada sección en orden


## Comentarios 
- La versión del sqlite no pude configurarla bien en colab, pero si logré terminar el examen con la version que tiene por defecto colab.
- Probé correr la misma configuración y me dio la version en local 3.38.2 