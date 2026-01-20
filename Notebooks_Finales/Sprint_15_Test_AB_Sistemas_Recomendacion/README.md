# SPRINT 15: AUDITORÍA DE EXPERIMENTACIÓN AVANZADA (TEST A/B)

### 🛡️ Escenario (Situation)
Se lanzó una prueba A/B para evaluar un nuevo sistema de recomendaciones. Sin embargo, los datos mostraban inconsistencias temporales y de asignación de usuarios.

### 🎯 Objetivo (Task)
Auditar la integridad técnica del experimento antes de interpretar los resultados de negocio.

### 🔧 Implementación Técnica (Action)
* **Auditoría de Muestra:** Verificación de balance 50/50 y superposición de usuarios entre pruebas concurrentes.
* **Funnel Analysis:** Evaluación de conversión en `product_page` vs `purchase`.
* **Z-Test:** Prueba de proporciones para validar significancia.

### 🚀 Resultados (Result)
**AUDITORÍA NEGATIVA.** Se declaró la prueba como INVÁLIDA debido a fallos en el diseño experimental (fechas coincidentes con promociones navideñas y desbalance de muestra). Se evitó una toma de decisión errónea.

---
**Stack:** `Python` `Experimental Design Audit` `Statistical Inference`