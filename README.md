# TC5053 · Actividad 6: Ingeniería de características

Libreta de análisis y transformación del conjunto `computer_prices.csv` para el curso Ciencia y analítica de datos, Tecnológico de Monterrey.

## Equipo

| Integrante | Matrícula |
| --- | --- |
| Federico Castro Zenteno | A01660986 |
| ______________________________ | __________________ |
| ______________________________ | __________________ |
| ______________________________ | __________________ |

Los demás integrantes se agregarán cuando se confirmen sus datos.

## Archivos

- `Actividad6FE_Completada.ipynb`: diez ejercicios, análisis en celdas de texto y resultados de ejecución.
- `computer_prices.csv`: datos proporcionados con la actividad (100,000 registros).
- `requirements.txt`: versiones de las bibliotecas utilizadas.

## Ejecución

1. Descarga el repositorio completo y conserva los archivos en la misma carpeta.
2. Usa Python 3.12 e instala las dependencias con `pip install -r requirements.txt`.
3. Abre `Actividad6FE_Completada.ipynb` en Jupyter o VS Code y ejecuta todas las celdas en orden.

En Google Colab, carga la libreta, el CSV y `requirements.txt`; instala las dependencias en una celda con `%pip install -q -r requirements.txt` antes de ejecutar todo. Si Colab solicita reiniciar el entorno tras la instalación, reinícialo primero.

Se usa 2026 como año fijo de referencia para calcular la antigüedad de los equipos.

## Procedencia y uso de IA

Esta versión se reconstruyó desde la plantilla `Actividad6FE.ipynb` y el CSV adjunto a la conversación original; no fue posible recuperar el archivo generado previamente. OpenAI Codex, basado en GPT-6, se utilizó para generar y depurar código, redactar análisis, verificar la ejecución y preparar la publicación. La libreta incluye la declaración correspondiente. El equipo debe revisar el contenido y completar los datos de sus integrantes antes de la entrega académica.

Los datos se incluyen para reproducir la actividad. No se atribuye una licencia nueva al conjunto de datos ni a la plantilla del curso.

## Validación

La libreta se ejecutó de principio a fin, en orden, sin errores ni advertencias en sus celdas. El resultado conserva 100,000 registros y contiene 54 columnas numéricas, sin valores faltantes ni infinitos y dentro del intervalo [0, 1] con tolerancia de redondeo de 1e-12.
