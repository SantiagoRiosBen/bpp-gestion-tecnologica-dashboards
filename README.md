# Biblioteca Pública Piloto (BPP) – Propuesta de Dashboards para la Gestión Tecnológica

Este repositorio contiene una **propuesta de solución analítica** desarrollada para el área de Gestión Tecnológica de la **Biblioteca Pública Piloto (BPP)**.  
Incluye un conjunto de dashboards creados en Power BI, acompañados de los datasets simulados utilizados para su construcción.

### **Importante:**  
> Todos los datos incluidos en este repositorio son **completamente simulados**, generados únicamente con fines académicos y demostrativos.  
> Ningún archivo, estructura o valor corresponde a información real de la Biblioteca Pública Piloto ni de ninguna de sus operaciones internas.

> Esta propuesta forma parte de la **entrega formal de prácticas** del **Máster en Análisis y Visualización de Big Data**, desarrollada por **Santiago Ríos Benjumea**.

---

## Objetivo del proyecto

El propósito de este proyecto es presentar un sistema de tableros que permita visualizar de manera integrada la información clave de una gestión tecnológica moderna, abarcando:

- Proyectos tecnológicos
- Operación TI
- Soporte técnico y tickets
- Alertas y riesgos tecnológicos
- Métricas y costos de servicios en la nube (AWS)

Los dashboards están diseñados para facilitar la toma de decisiones estratégicas, tácticas y operativas en un entorno institucional.

---

## Contenido del repositorio

El repositorio está organizado en la siguiente estructura:

```
├── datasets/
│ ├── aws/
│ │ ├── aws_alertas_seguridad.csv
│ │ ├── aws_costos_diarios.csv
│ │ └── aws_metricas_diarias.csv
│ │
│ ├── maestros/
│ │ ├── dim_areas_organizacionales.csv
│ │ ├── dim_componentes_tecnologicos.csv
│ │ └── dim_servicios_aws.csv
│ │
│ ├── operativo/
│ │ ├── incidentes_infraestructura_local.csv
│ │ └── tickets_soporte_ti.csv
│ │
│ └── proyectos/
│ ├── hitos_proyectos_ti.csv
│ ├── presupuesto_ti_mensual.csv
│ ├── proyectos_ti.csv
│ └── riesgos_ti.csv
│
├── BPP_Dashboards.pbix
├── README.md
└── .gitkeep
```

---

## Descripción de carpetas

### 1. datasets/aws
Archivos simulados relacionados con el comportamiento de servicios en la nube:
- Costos diarios
- Alertas de seguridad
- Métricas operativas

### 2. datasets/maestros
Tablas dimensionales utilizadas para estructurar relaciones:
- Áreas organizacionales
- Componentes tecnológicos
- Servicios AWS

### 3. datasets/operativo
Datos operativos simulados del área TI:
- Incidentes en infraestructura local
- Tickets de soporte

### 4. datasets/proyectos
Información correspondiente al portafolio de proyectos simulados:
- Seguimiento a hitos
- Presupuesto
- Información general de proyectos
- Evaluación de riesgos

### Archivo principal
**BPP_Dashboards.pbix** contiene todos los tableros propuestos y debe abrirse en Power BI Desktop.

---

## Tableros incluidos

El archivo PBIX contiene cuatro tableros principales:

### 1. Tablero Estratégico – Panorama General de la Gestión Tecnológica
Incluye indicadores como:
- Avance global del portafolio TI
- Proyectos en tiempo, en presupuesto y con riesgo alto
- Presupuesto asignado vs ejecutado
- Riesgos por componente tecnológico
- Proyectos por fase
- Indicadores AWS (costo total, uptime y alertas)

### 2. Tablero Táctico – Gestión Tecnológica
Contiene:
- Proyectos activos
- Avance promedio
- Tickets abiertos
- Tiempo promedio de resolución
- Tickets por categoría y por mes
- Avance por componente

### 3. Tablero Operativo – Soporte y Casos TI
Incluye:
- Casos abiertos, cerrados y vencidos
- Casos por categoría
- Casos por departamento
- Casos por mes

### 4. Tablero de Alertas y Riesgos Tecnológicos
Presenta:
- Alertas activas y críticas
- Tiempo promedio de resolución
- Riesgos identificados
- Alertas por severidad y por semana
- Riesgos por categoría

---

## Requisitos para abrir el proyecto

- Power BI Desktop (versión reciente recomendada)
- Clonar o descargar este repositorio

Para descargar:

[git clone](https://github.com/SantiagoRiosBen/bpp-gestion-tecnologica-dashboards.git)

Luego abrir el archivo:


Power BI reconocerá automáticamente la estructura de los datasets.

---

## Uso del proyecto

1. Descargue o clone el repositorio.
2. Abra **BPP_Dashboards.pbix** en Power BI Desktop.
3. Si Power BI lo solicita:
   - Verifique o actualice las rutas en Transformar datos > Configuración de origen.
4. Explore cada tablero desde las pestañas inferiores.
5. Adapte o modifique según las necesidades de su institución o estudio.

---

## Autor

**Santiago Ríos Benjumea**  
Propuesta académica presentada como entrega de prácticas del **Máster en Análisis y Visualización de Big Data**.  
Datos 100% simulados, sin relación con información real de la Biblioteca Pública Piloto.
