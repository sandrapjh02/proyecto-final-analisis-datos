# Woman Consulting Group  Proyecto Final Datathon Academico

Este repositorio contiene el desarrollo completo del reto propuesto en el **Datathon Academico de Conexion Mujeres TIC**, en el que un equipo multidisciplinario aplica tecnicas de analisis de datos, visualizacion y metodologias agiles para resolver un problema empresarial real con impacto nacional.

---

## Descripcion del reto

Actuamos como un equipo de analisis de datos dentro de una empresa consultora ficticia. A partir de un dataset real sobre empresas colombianas, propusimos hipotesis, analizamos informacion financiera y formulamos soluciones estrategicas para identificar sectores y regiones con mayor impacto economico en Colombia.

---

## Objetivo general

Identificar los **sectores y regiones con mayor impacto económico en Colombia**mediante el análisis de los **ingresos, ganancias, activos y patrimonio** de las principales empresas del país.

---

##  Hipotesis

> *"1. Las ganancias de las empresas más grandes de Colombia están concentradas en un número reducido de actividades económicas y macrosectores."*
> 
> *"2. El desempeño financiero de las principales empresas de Colombia está significativamente influenciado por su ubicación geográfica, lo que refleja desigualdades estructurales en la generación de ingresos y acumulación de patrimonio."*

---

##  Enfoque metodologico

El proyecto se desarrollo en las siguientes fases:

1. **Definicion del problema e hipotesis**
2. **Exploracion y limpieza de datos (EDA)**
3. **Analisis descriptivo y visual**
4. **Modelado predictivo con regresion**
5. **Desarrollo de dashboard interactivo**
6. **Elaboracion de storytelling (presentacion TED)**
7. **Gestion del proyecto con metodologia agil (SCRUM)**

---

##  Analisis y modelado

### Variables predictoras
- Ingresos operacionales
- Total activos
- Total patrimonio
- Macrosector
- Region
- Supervisor
- Actividad economica

### Variable objetivo
- Ganancia (Perdida)

### Preprocesamiento
- Estandarizacion de variables numericas (media = 0, desviacion estandar = 1)
- Transformacion de variables categoricas a binarias
- Eliminacion de outliers para mejorar rendimiento del modelo

### Modelos evaluados
- Regresion Lineal
- Regresion Ridge
- Random Forest
- Gradient Boosting
- Soporte Vectorial (SVR)
- K-Neighbors

### Resultados destacados
- **Random Forest** y **Gradient Boosting** mostraron mayor precision (R) y menor error absoluto (MAE)
- Las regiones influyen significativamente en la ganancia 
- Las actividades mas rentables fueron comercio, energia, servicios financieros y comunicaciones

---

##  Solucion propuesta

Desarrollamos un modelo predictivo que permite:

- Estimar ganancias de empresas con base en su tamano financiero, actividad economica y ubicacion regional
- Identificar sectores rentables para orientar decisiones de inversion o politicas publicas
- Detectar anomaleas financieras entre empresas
- Predecir el desempeno financiero de nuevas companias

---

##  Recomendaciones estrategicas

- **Gobierno y reguladores:** identificar concentracion economica y priorizar politicas para regiones rezagadas
- **Empresas y consultoras:** usar benchmarking financiero para evaluar oportunidades de inversion
- **Analistas de datos:** ampliar el analisis con variables como empleo y exportaciones; explorar modelos como XGBoost o redes neuronales

---

##  Equipo de trabajo

| Nombre                  | Rol                                    |
|-------------------------|----------------------------------------|
| Sandra Jimenez          | Scrum Master                           |
| Carolina Diartt         | Product Owner                          |
| Anycliz Garcia          | Analista de datos                      |
| Luz Mary Marriaga       | Analista de datos                      |
| Maribel Diaz            | Analista de datos                      |
| Maria Isabel Matute     | Especialista en visualizacion          |
| Ericka Zarate           | Especialista en visualizacion          |
| Maria Paz Molina        | Especialista en visualizacion          |
| Yurani Hurtado          | Disenadora                             |
| Yennifer Padilla        | Disenadora                             |
| Liseth De la Hoz        | Disenadora                             |
| Vanessa Castellanos     | Disenadora                             |
| Jessica Cardenas        | Disenadora                             |

---

##  Herramientas utilizadas

- **Python** (pandas, seaborn, matplotlib)
- **Power BI** (dashboard interactivo) Version 2.144.679.0 64-bit(Junio 2025)
- **GitHub** (control de versiones, ramas colaborativas)
- **Trello** (gestion agil con SCRUM)
- **Canva** (diseno visual y presentaciones)
- **Metodologia agil** (SCRUM, dailys y entregables iterativos)

---

##  Instalacion
- **git clone https://github.com/sandrapjh02/proyecto-final-analisis-datos**
- **cd proyecto-final-analisis-datos**
- **pip install pandas matplotlib seaborn numpy scikit-learn**

 
---

##  Estructura del repositorio

```bash
+-- BD/             # Dataset en formato CSV, Scripts del modelo ML
+-- visualizacion/  # Power BI (.pbix) y visualizaciones exportadas
+-- presentacion/   # Guion TED, presentacion, diseno visual e informe tecnico.
+-- README.md       # Este documento
