Análisis de Datos del Servicio Bicing Barcelona

Este proyecto es un análisis completo del servicio de bicicletas compartidas Bicing en Barcelona durante el año 2024. Abarca desde la limpieza de datos crudos hasta la visualización de KPIs e insights clave en Tableau.

Objetivo

Detectar patrones de uso, identificar estaciones con problemas de disponibilidad, proponer mejoras operativas y comunicarlo de forma visual e interactiva.

Tecnologías y herramientas

Python (pandas, matplotlib, seaborn, folium)

Jupyter Notebooks para limpieza, análisis y exportación

Tableau Public para visualización y dashboard final

GitHub para documentación del proyecto

Estructura del repositorio

/portfolio
├── data
│   ├── raw_data             # Datos originales mensuales (CSV)
│   ├── processed_data        # Datos tratados y enriquecidos
│   └── export_tableau        # Datos listos para Tableau
├── data_cleaning_1.ipynb       # Limpieza general de datos
├── data_cleaning_2.ipynb       # Correcciones y validaciones extra
├── Export_tableau.ipynb        # Generación de CSV para Tableau
├── kpis_1.ipynb                # KPIs principales y ocupación mensual
├── kpis_2.ipynb                # Estacionalidad, fluctuaciones, zonas problema

KPIs y visualizaciones generadas:

Ocupación media mensual

Estaciones más y menos ocupadas

Uso relativo mensual

Fluctuaciones diarias (desviación estándar)

Estaciones problemáticas (saturadas y vacías)

Zonas con alta/baja disponibilidad por mes

Estaciones con comportamiento recurrente extremo

Dashboards en Tableau Public

https://public.tableau.com/app/profile/miguel.roces/viz/Dashboard_Bicing_/Dashboard1

Autor

Miguel Roces Díaz

Data Scientist | Portfolio Project 







Data Analysis of Bicing Barcelona Service (English)

This project is a full analytics workflow on the shared bike system Bicing in Barcelona (2024). It covers everything from raw data cleaning to KPI design and Tableau dashboards.

Goal

To detect usage patterns, highlight problematic stations, suggest operational improvements and communicate insights visually.

Technologies used

Python (pandas, matplotlib, seaborn, folium)

Jupyter Notebooks for processing and exporting data

Tableau Public for interactive dashboards

GitHub for documentation

Project structure

/portfolio
├── data
│   ├── raw_data             # Original monthly CSVs
│   ├── processed_data        # Cleaned & enriched data
│   └── export_tableau        # Data ready for Tableau
├── data_cleaning_1.ipynb       # Main cleaning steps
├── data_cleaning_2.ipynb       # Extra corrections
├── Export_tableau.ipynb        # Export for Tableau
├── kpis_1.ipynb                # Key metrics and monthly use
├── kpis_2.ipynb                # Seasonality and problem zones

KPIs and visuals:

Monthly average occupancy

Most/least used stations

Monthly relative usage

Daily fluctuation (std dev)

Problematic stations: saturated/empty

Hotspot zones by availability type

Recurrent extreme behavior stations



Tableau Public dashboards

https://public.tableau.com/app/profile/miguel.roces/viz/Dashboard_Bicing_/Dashboard1

Author

Miguel Roces Díaz

Data Scientist | Portfolio Project
