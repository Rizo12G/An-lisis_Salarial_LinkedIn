# Análisis Salarial de Vacantes en LinkedIn
Análisis de patrones salariales de vacantes en LinkedIn: tendencias por puesto, ubicación e industria (ETL, EDA).

---

## Descripción del Proyecto
Este proyecto analiza los patrones salariales de vacantes publicadas en LinkedIn para identificar tendencias por puesto, ubicación e industria. La información generada permite a los buscadores de empleo y a las empresas tomar decisiones más informadas sobre rangos salariales y oportunidades profesionales.

---

## Contexto y Objetivo
Comprender los salarios del mercado laboral ayuda a tomar decisiones estratégicas:

- **Por puesto:** Roles híbridos o especializados (SQL, Data Visualization) se ubican en rangos medio-altos. Data Analyst / $100K es el mejor pagado según los datos.  
- **Por empresa:** Empresas tecnológicas consolidadas (EdgeLink, Insight Global) ofrecen salarios superiores a $120K, mientras que otras rondan los $70K.  
- **Por ubicación:** Ciudades con alto costo de vida y concentración tecnológica (Burbank, CA; Washington D.C.) ofrecen más de $120K, mientras que Raleigh, NC o Ann Arbor, MI pagan entre $70K–$90K.  
- **Por modalidad:** Empleos híbridos o remotos presentan mejores salarios promedio ($88K–$93K) que los presenciales ($84K).

**Conclusión:** El salario depende principalmente de la ubicación, modalidad de trabajo, empresa y tipo de rol. Roles especializados, híbridos y en empresas/ciudades tecnológicas suelen ofrecer las mejores oportunidades.

---

## Desarrollo del Proyecto
El análisis se desarrolló en tres etapas principales:

### 1. ETL (Extract, Transform, Load)
**Archivo:** `Limpieza_y_Transformacion_de_datos.ipynb`  
- Normalización de nombres y formatos  
- Verificación de datos nulos y duplicados  
- Manejo de valores faltantes  
- Transformación de columnas para análisis

### 2. Agregación y Preparación de Datos
**Archivo:** `Agregar_Agrupar_Datos.ipynb`  
- Agrupación de vacantes por puesto, empresa, ubicación y modalidad  
- Cálculo de métricas salariales promedio y rangos  
- Preparación de datasets listos para análisis exploratorio

### 3. Análisis Exploratorio (EDA)
**Archivo:** `Analisis_Exploratorio.ipynb`  
- Visualización de tendencias salariales  
- Identificación de patrones por ubicación, empresa, modalidad y tipo de rol  
- Conclusiones y recomendaciones salariales

---

## Resumen Visual de Hallazgos
- Salarios van de $55K a $120K, concentrándose entre $80K y $100K.  
- Roles híbridos o especializados destacan en el rango medio-alto.  
- Empresas tecnológicas consolidadas pagan más de $120K.  
- Ubicaciones con alto costo de vida presentan mejores salarios.  
- Empleos híbridos/remotos tienen mejores remuneraciones promedio que los presenciales.

---

## Archivos del Proyecto
- `Data/` : Carpeta con datasets originales y procesados  
- `Analisis_Exploratorio.ipynb` : Análisis exploratorio (EDA)  
- `Limpieza_y_Transformacion_de_datos.ipynb` : Proceso ETL  
- `Agregar_Agrupar_Datos.ipynb` : Preparación y agregación de datos  
- `README.md` : Este archivo explicativo

---

## Dependencias
El proyecto utiliza las siguientes librerías de Python:  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  

## Desarollador 
 __Gabriel Rizo__