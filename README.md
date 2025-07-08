## title: "🚀 Arquitectura de Datos en Azure con Synapse Analytics 🌟"

¡Bienvenid@ a este repositorio! Aquí encontrarás tres laboratorios prácticos para construir una **arquitectura de datos moderna** en Microsoft Azure. Aprenderás a crear **pipelines de datos** usando servicios como **Azure Data Factory**, **Azure Data Lake Storage Gen2**, **Azure Synapse Analytics** y más. 🎉

## 📚 Resumen de los Laboratorios

- **Laboratorio I** 🛠️: Configura los cimientos de tu entorno Azure: grupo de recursos, cuenta de almacenamiento, Data Factory y Synapse Analytics.
- **Laboratorio II** 📥: Crea un pipeline en Azure Data Factory para ingerir datos desde la *LandingZone* a la capa *Bronze*. ¡Perfecto para procesos ETL! 🔄
- **Laboratorio III** 📊: Transforma datos con Spark Pools y construye una base de datos SQL serverless en Synapse para análisis avanzados. ✨

## 📋 Prerrequisitos

- 🌐 Suscripción activa de **Microsoft Azure** (recomendamos *Azure for Students*).
- 🔑 Acceso al **Azure Portal** y **Synapse Studio**.
- 📂 Archivos de datos del curso (reemplaza los placeholders en `/Data`).
- 🧠 Conocimientos básicos de ETL/ELT y herramientas de Azure.

## 🛠️ Estructura del Repositorio

- **Labs/** 📄: PDFs de los laboratorios (`Laboratorio_I.pdf`, `Laboratorio_II.pdf`, `Laboratorio_III.pdf`).
- **Scripts/** 💻: Scripts SQL (`SQL_covid_worldwide.sql`, `SQL_best_recovery.sql`) y notebooks de Spark (`nbk_covid_BZ_to_SZ.ipynb`, `nbk_covid_SZ_to_GZ.ipynb`).
- **Data/** 📈: Archivos de datos de ejemplo (`Athletes.csv`, `covid_worldwide_rc.csv`) o placeholders. Obtén los originales del aula virtual.
- **Pipelines/** 🔗: Configuraciones de pipelines como `LZ_to_BZ_Athletes_pipeline.json` para Azure Data Factory.
- **Docs/** 📖:
  - `setup_guide.md`: Guía para configurar tu entorno Azure.
  - `prerequisites.md`: Lista de requisitos para empezar.
  - `troubleshooting.md`: Soluciones a problemas comunes, como errores con el proveedor Microsoft.Synapse.

## 🚀 Instrucciones de Configuración

1. Sigue `Docs/setup_guide.md` para crear el grupo de recursos, cuenta de almacenamiento, Data Factory y Synapse Analytics. 🏗️
2. Carga los archivos de datos al contenedor `datotokyoolympicsgps` en Azure Data Lake Storage Gen2. 📤
3. Importa las configuraciones de pipelines desde `/Pipelines/` a Azure Data Factory. 🔄
4. Ejecuta los notebooks y scripts SQL en Synapse Studio según las instrucciones de los laboratorios. 💾

## 🏃‍♂️ Cómo Ejecutar los Pipelines

- **Lab I** 🛠️: Configura los recursos base y verifica el acceso a Synapse Studio.
- **Lab II** 📥: Usa Azure Data Factory para mover datos de `LandingZone` a `Bronze`. Importa `LZ_to_BZ_Athletes_pipeline.json` o sigue el PDF.
- **Lab III** 📊: Transforma datos (Bronze → Silver → Gold) con Spark y crea bases de datos SQL serverless.

## 🤝 Contribuciones

¡Tu feedback es bienvenido! Crea un *issue* o envía un *pull request* para mejorar este repositorio. 💡

## 📜 Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE). ✅
