# ✈️ Análisis Predictivo de Reservas en una Empresa de Viajes

Este proyecto aplica técnicas de Machine Learning para predecir el comportamiento de los clientes de una empresa ficticia de viajes.

---

## 📌 Objetivos del Proyecto

- Predecir si un cliente reservará un tour (clasificación)
- Estimar cuánto pagará en caso de reservar (regresión)

---

## 🧾 Dataset Sintético

El conjunto de datos fue generado con Python, simulando 10,000 registros de clientes con las siguientes variables:

- Edad, Ingresos mensuales
- Visitas y tiempo en la web
- Cantidad de tours vistos
- Promociones usadas
- ¿Reservó tour? (0/1)
- Monto pagado (solo si reservó)

📁 Archivo: `dataset/dataset_viajes.csv`

---

## 📊 Estructura del Proyecto

```
ML_Viajes_Reservas/
├── dataset/
│   └── dataset_viajes.csv
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Regresion.ipynb
│   └── 03_Clasificacion.ipynb
├── informe/
│   └── Informe_ML_Viajes.docx
├── README.md
└── requirements.txt
```

---

## 🧪 Modelos Aplicados

### 🔹 Regresión
- Regresión Lineal
- Regresión Polinómica

### 🔸 Clasificación
- Random Forest

---

## 📈 Resultados

| Modelo                | MSE / Accuracy | R² / AUC |
|----------------------|----------------|----------|
| Regresión Lineal     | ...            | ...      |
| Regresión Polinómica | ...            | ...      |
| Random Forest        | 87.6% Accuracy | 0.94 AUC |

---

## 👤 Elaborado por:
Luis Jaancarlos Lengua Hernández  
Curso: Machine Learning I – Instituto Continental  
2025
