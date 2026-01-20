# SPRINT 13: ESTRATEGIA DE RETENCIÓN CON MACHINE LEARNING (MODEL FITNESS)

### 🛡️ Escenario (Situation)
La cadena de gimnasios "Model Fitness" enfrentaba una alta tasa de cancelación. La estrategia de retención era reactiva en lugar de proactiva.

### 🎯 Objetivo (Task)
Desarrollar un modelo de Machine Learning para predecir la probabilidad de fuga (churn) del mes siguiente y segmentar a los usuarios para personalizar ofertas.

### 🔧 Implementación Técnica (Action)
* **Aprendizaje No Supervisado:** Clustering con K-means para identificar 5 perfiles de usuario.
* **Aprendizaje Supervisado:** Regresión Logística y Random Forest para predecir binariamente la cancelación.
* **Dendrogramas:** Visualización jerárquica de la vinculación de clientes.

### 🚀 Resultados (Result)
Se identificó que los usuarios de "servicios adicionales" (café, masajes) tienen mayor retención. El modelo permite intervenir antes de que el cliente abandone.

---
**Stack:** `Python` `Scikit-Learn` `K-Means` `Dendrogram`