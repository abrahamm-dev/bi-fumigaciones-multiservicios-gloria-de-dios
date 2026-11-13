# bi-fumigaciones-multiservicios-gloria-de-dios
# 📊 Sistema de Inteligencia de Negocios (BI) — Fumigaciones Multiservicios Gloria de Dios C.A.

Proyecto integral de análisis de datos y Business Intelligence desarrollado bajo la metodología del **Ciclo de Vida de Kimball**, orientado a transformar la gestión operativa, comercial y de inventario de *Fumigaciones Multiservicios Gloria de Dios C.A.* mediante una **Única Versión de la Verdad (SVOT)**.

---

## 🎯 Problema de Negocio y Objetivos

La organización operaba con registros manuales y hojas de cálculo aisladas[cite: 10], lo que generaba tres retos principales:
1. **Opacidad en inventario:** Falta de trazabilidad entre los insumos químicos aplicados, el tipo de plaga y la superficie tratada ($m^2$).
2. **Fuga de renovaciones:** Ausencia de alertas para el seguimiento de vencimiento de certificados sanitarios en clientes comerciales e industriales.
3. **Carga operativa manual:** Más de 12 horas mensuales invertidas en la consolidación manual de ingresos y comisiones técnicas.

**Objetivo del Proyecto:** Diseñar e implementar una arquitectura analítica desacoplada que automatice la extracción de datos operacionales y entregue tableros ejecutivos para la toma de decisiones estratégicas.

---

## 🛠️ Stack Tecnológico (100% Open Source)

Toda la solución fue arquitectada sobre herramientas de código abierto para garantizar **$0 USD en costos de licenciamiento**:

* **Base de Datos Transaccional (OLTP) y Data Warehouse (OLAP):** PostgreSQL 13.
* **Extracción, Transformación y Carga (ETL):** Pentaho Data Integration (PDI 9.0 CE / Kettle).
* **Motor OLAP Multidimensional:** Mondrian.
* **Capa de Visualización y Reportes (Front-End):** Pentaho BA Server 9.0 CE.
* **Modelado de Datos:** Esquema en Estrella (*Star Schema*) con tablas de hechos (`fact_services`, `fact_inventory`) y dimensiones conformadas (`dim_time`, `dim_customer`, `dim_chemical`, `dim_pest`, `dim_salesrep`, `dim_status`).

---

## 📂 Estructura del Repositorio (Entregables)

El proyecto está documentado de forma secuencial siguiendo las fases del diplomado:

* 📁 **[`01-project-charter/`](./01-project-charter)**: Constitución del proyecto, adaptación del Business Model Canvas a BI y evaluación financiera (TCO, Beneficios Anuales, ROI del 361.5% y Payback de 6.3 meses bajo la regla 2:1).
* 📁 **[`02-vision-sistema/`](./02-vision-sistema)**: Alcance funcional y técnico del sistema analítico, perfiles de stakeholders y límites frente al entorno transaccional.
* 📁 **[`03-requerimientos-negocio-bri/`](./03-requerimientos-negocio-bri)**: Levantamiento de requerimientos analíticos (`BRI-001` a `BRI-006`), fichas técnicas, métricas clave (KPIs) y mockups de tablas cruzadas (*crosstabs*).
* 📁 **[`04-arquitectura-bi/`](./04-arquitectura-bi)**: Diseño conceptual y técnico de las 5 capas de la solución, flujos ETL, gobernanza de datos (*Data Steward*) y matriz de seguridad por roles.

---

## 📈 Impacto Financiero Proyectado

* **Inversión Inicial (TCO):** $10,000 USD (desarrollo e implementación Open Source).
* **Mantenimiento Anual:** $1,000 USD/año.
* **Beneficios Estimados:** $20,000 USD/año (incremento en re-fumigaciones comerciales, reducción del 15% en mermas de químicos y ahorro de horas administrativas).
* **ROI (a 3 años):** **361.5%** | **Período de Recuperación (Payback):** **~6.3 meses**.

---

## 👤 Autor

**Abraham Javier Arguello Rivas**  
*Data Analyst & Business Intelligence Specialist*  
🔗 Conecta conmigo en [LinkedIn] (https://www.linkedin.com/in/abraham-arguello-504958400/)
