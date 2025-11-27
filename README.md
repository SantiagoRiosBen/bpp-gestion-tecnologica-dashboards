# Biblioteca Pública Piloto (BPP) – Gestión Tecnológica Dashboards

Este repositorio contiene un conjunto de dashboards desarrollados en Power BI para el análisis estratégico, táctico y operativo de la Gestión Tecnológica de la Biblioteca Pública Piloto (BPP).  
Incluye los datasets utilizados, el archivo .pbix con los tableros construidos y la estructura de carpetas organizada para facilitar su consulta y reutilización.

---

## Objetivo del proyecto

El propósito de este proyecto es centralizar, visualizar y analizar la información clave relacionada con:

- Proyectos tecnológicos
- Operación TI
- Alertas y riesgos tecnológicos
- Costos y métricas de servicios en la nube (AWS)

Los dashboards permiten monitorear indicadores clave, facilitar la toma de decisiones y ofrecer una visión integral del estado actual de la gestión tecnológica de la BPP.

---

## Contenido del repositorio

El repositorio está organizado en la siguiente estructura:

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


### Descripción de carpetas

#### 1. datasets/aws
Contiene información relacionada con el consumo y monitoreo de servicios AWS:
- Costos
- Alertas de seguridad
- Métricas operativas

#### 2. datasets/maestros
Incluye tablas dimensionales utilizadas para relaciones y categorizaciones:
- Áreas organizacionales
- Componentes tecnológicos
- Servicios AWS

#### 3. datasets/operativo
Datos operativos del área TI:
- Incidentes de infraestructura local
- Tickets de soporte

#### 4. datasets/proyectos
Información del portafolio de proyectos tecnológicos:
- Seguimiento de hitos
- Presupuesto mensual
- Información general de proyectos
- Gestión de riesgos

#### Archivo principal
**BPP_Dashboards.pbix** contiene todos los dashboards desarrollados y es el archivo que debe abrirse en Power BI Desktop.

---

## Tableros incluidos

El archivo PBIX contiene cuatro tableros principales:

### 1. Tablero Estratégico – Panorama General de la Gestión Tecnológica
Incluye:
- Avance global del portafolio TI
- Proyectos en tiempo
- Proyectos dentro del presupuesto
- Proyectos con riesgo alto
- Presupuesto asignado vs ejecutado
- Riesgos por componente tecnológico
- Proyectos por fase
- Indicadores AWS:
  - Costo total
  - Uptime promedio
  - Alertas activas
- Alertas por severidad

### 2. Tablero Táctico – Gestión Tecnológica
Contiene:
- Proyectos activos
- Porcentaje de avance promedio
- Tickets abiertos
- Tiempo promedio de resolución
- Avance por componente tecnológico
- Tickets por categoría
- Tickets abiertos por mes

### 3. Tablero Operativo – Soporte y casos TI
Incluye:
- Casos abiertos
- Casos cerrados
- Casos vencidos
- Casos por categoría
- Casos por departamento
- Casos por mes

### 4. Tablero de Alertas y Riesgos Tecnológicos
Presenta:
- Alertas activas
- Alertas críticas
- Tiempo promedio de resolución
- Riesgos identificados
- Alertas por severidad
- Riesgos por categoría
- Alertas por semana

---

## Requisitos para abrir el proyecto

- Power BI Desktop (versión reciente recomendada)
- Clonar o descargar este repositorio

Para descargar el proyecto:

git clone (https://github.com/SantiagoRiosBen/bpp-gestion-tecnologica-dashboards.git)

Luego abrir el archivo:

`BPP_Dashboards.pbix`


Power BI detectará automáticamente los datasets porque están organizados en las rutas esperadas.

---

## Uso del proyecto

1. Descargue o clone el repositorio.
2. Abra **BPP_Dashboards.pbix**.
3. Si Power BI lo solicita:
   - Verifique las rutas en Transformar datos > Configuración de origen.
4. Explore los tableros mediante las pestañas inferiores.
5. Personalice según las necesidades de su organización.

---

## Autor

Santiago Ríos Benjumea  
Proyecto de prácticas para la gestión tecnológica de la BPP.
