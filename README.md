# EdTech Learning Analytics

Proyecto de análisis de datos educativos enfocado en estudiar el comportamiento de los estudiantes, el rendimiento académico, la participación en cursos y la predicción de resultados mediante técnicas de ciencia de datos.

## Tecnologías utilizadas

- Python y Jupyter Notebook
- Pandas y herramientas de análisis de datos
- Apache Spark
- SQL y SQLite
- Herramientas de visualización y análisis geoespacial
- Power BI

## Estructura del proyecto

- `datos/crudos/`: datasets originales.
- `datos/externos/`: fuentes de datos externas.
- `datos/geoespaciales/`: información geográfica.
- `datos/procesados/`: datasets transformados y preparados.
- `notebooks/`: análisis, limpieza, ingeniería de características, gobierno de datos y predicción.
- `scripts/`: scripts auxiliares.
- `sql/`: consultas SQL.
- `resultados/`: reportes, gráficas y mapas.
- `visualizaciones/`: dashboard de Power BI.

## Instalación

**1. Clonar el repositorio**

```bash
git clone https://github.com/USUARIO/edtech_learning_analytics.git
cd edtech_learning_analytics
```

Sustituir `USUARIO` por el propietario del repositorio.

**2. Crear un entorno virtual**

```bash
python -m venv .venv
```

**3. Activar el entorno virtual**

Windows (PowerShell):

```powershell
.\.venv\Scripts\Activate.ps1
```

Linux/macOS:

```bash
source .venv/bin/activate
```

**4. Instalar las dependencias**

```bash
python -m pip install -r requirements.txt
```

**5. Ejecutar los notebooks**

Abrir el proyecto en Visual Studio Code, instalar la extensión Jupyter y seleccionar el intérprete Python del entorno `.venv`.

Los notebooks se encuentran numerados del `01` al `08` para facilitar su identificación.

## Consideraciones

- Utilizar una versión compatible de Python.
- Revisar la configuración de Java si se ejecuta Apache Spark.
- Mantener la estructura de carpetas al ejecutar los notebooks.
- Utilizar Power BI Desktop para abrir los archivos `.pbix`.
- Verificar que las rutas de lectura y escritura de datos sean relativas al proyecto.
