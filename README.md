# 📊 Predicción de Churn en Telecom X

## 📌 Descripción del Proyecto

Este proyecto aborda el problema de la cancelación de clientes (*churn*) en **Telecom X**, una empresa de telecomunicaciones.  
El objetivo es identificar los factores que impulsan el churn y construir modelos predictivos robustos para anticipar qué clientes tienen mayor probabilidad de abandonar la empresa, permitiendo así intervenciones de retención más efectivas.

---

## 🗂️ Estructura de los Datos

- **Registros:** 7,267 clientes  
- **Variables:** 21 columnas con información demográfica, servicios contratados, historial de pagos y estado de churn

---

## 🔍 Principales Hallazgos

- El **55%** de los clientes tiene contrato *Month-to-month*, segmento con mayor fuga.
- Clientes con **menos de 12 meses** de antigüedad tienen hasta **3 veces más probabilidad** de churn.
- No contar con servicios adicionales (`OnlineSecurity`, `TechSupport`, `DeviceProtection`) **incrementa el riesgo**.
- El método de pago **"Electronic check"** tiene la tasa de churn más alta (~34%).
- El tipo de internet **"Fiber optic"** presenta mayor churn que *DSL*.
- **Cargos mensuales altos** y **cargos totales bajos** son típicos de clientes nuevos y de alto riesgo.



## 💡 Recomendaciones de Negocio

- **Migrar contratos "Month-to-month"** a planes anuales mediante incentivos y descuentos.
- **Promover servicios adicionales** (seguridad, soporte, protección de dispositivos) con bundles y ofertas para clientes nuevos.
- **Campañas dirigidas a clientes con "Electronic check"** para migrar a métodos automáticos (tarjeta/crédito) con beneficios iniciales.
- **Programa de fidelización por antigüedad**: recompensas a los 6 y 12 meses para reducir churn temprano.
- **Alertas proactivas**: disparar intervenciones cuando un cliente cumpla condiciones críticas (tenure bajo, contrato M2M, Electronic check).

---

## 🧩 Segmentos de Clientes en Riesgo

### 1. Contrato "Month-to-month", <12 meses y pago "Electronic check"
- 📉 Mayor tasa de cancelación  
- 🛠 **Acción:** Incentivar migración a contratos anuales y pagos automáticos.

### 2. Usuarios de "Fiber optic" sin servicios adicionales
- 📉 Churn superior al promedio  
- 🛠 **Acción:** Promocionar bundles de seguridad y soporte.

### 3. Cargos mensuales altos y cargos totales bajos
- 📉 Nuevos con paquetes premium, riesgo de baja integración  
- 🛠 **Acción:** Onboarding personalizado y seguimiento inicial.

### 4. Clientes sin dependientes ni pareja, especialmente "Senior Citizens"
- 📉 Mayor propensión al churn  
- 🛠 **Acción:** Beneficios exclusivos y comunicación personalizada.

### 5. Clientes sin servicio de internet
- 📈 Oportunidad para *upselling* de servicios digitales.
