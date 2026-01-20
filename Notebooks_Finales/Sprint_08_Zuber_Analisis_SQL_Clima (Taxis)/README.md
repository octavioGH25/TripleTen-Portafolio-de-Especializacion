# SPRINT 08: ANÁLISIS SQL Y FACTORES EXTERNOS (ZUBER)

### 🛡️ Escenario (Situation)
La empresa de viajes compartidos "Zuber" está lanzándose en Chicago. Necesitaba entender la competencia y, específicamente, validar si el mal tiempo afectaba la duración de los viajes para ajustar sus algoritmos de precios.

### 🎯 Objetivo (Task)
Auditar datos extraídos mediante SQL para identificar a los líderes del mercado y validar estadísticamente la hipótesis de impacto climático.

### 🔧 Implementación Técnica (Action)
* **Parsing de Datos SQL:** Procesamiento de resultados de consultas de bases de datos relacionales.
* **Benchmarking:** Ranking de las principales empresas de taxis (Flash Cab vs resto).
* **Prueba de Hipótesis:** Aplicación de T-test de Student para comparar la duración de viajes en días lluviosos vs. despejados.

### 🚀 Resultados (Result)
Se identificó a "Flash Cab" como el competidor dominante. Se demostró estadísticamente que la lluvia incrementa la duración de los viajes, validando la necesidad de tarifas dinámicas por clima.

---
### › TECNOLOGÍAS
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-Hypothesis-red?style=for-the-badge)