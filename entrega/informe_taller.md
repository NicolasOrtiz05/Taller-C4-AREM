# 📄 Informe Técnico del Taller

## 🔖 Nombre del Taller
_Taller 3 - Arquitectura Actual del Sistema con el Modelo C4_

## 👥 Integrantes del equipo
- Edwin Alejandro Gutierrez Rodriguez
- Samuel Espitia Cruz
- Nicolas Stiven Ortiz Cortes

## 🧠 Descripción general del trabajo
El objetivo principal del taller fue aplicar la metodología C4 Model para representar de manera estructurada la arquitectura de sistemas en diferentes niveles de detalle. Inicialmente, se realizó un ejercicio guiado con un caso hipotético (RedExpress) para comprender cómo identificar actores, sistemas y contenedores dentro de una organización de base tecnológica.

Posteriormente, el equipo aplicó este mismo enfoque al sistema de Gestión de Adquisiciones de la Universidad de La Sabana, considerado como el cliente real en el contexto del curso.
La actividad se desarrolló de forma colaborativa, combinando sesiones de discusión en equipo con el uso de herramientas de modelado digital como draw.io.

## 🔧 Proceso de desarrollo
Para la construcción del C1 (Vista de Contexto) del sistema de adquisiciones de la Universidad de La Sabana, el equipo inició con una lectura y análisis del Manual de Adquisición de Bienes y Servicios y de la Presentación de Capacitación en Procesos de Adquisiciones. A partir de estos documentos se identificaron los actores principales, los sistemas involucrados y las relaciones entre ellos.

El modelado se realizó en draw.io, iniciando con los actores más evidentes (Unidad Solicitante, Jefatura de Adquisiciones, Proveedores) y luego se fueron incorporando instancias de validación y control (Decanos, Comité/Subcomisión, Plataforma INSPEKTOR).

## 🧩 Análisis del modelo propuesto
Incluya un análisis sobre:
- **Cómo se estructura el modelo entregado:** El modelo C1 se estructuró mostrando de manera clara los distintos actores que participan en el proceso de adquisiciones y las relaciones que mantienen entre sí. Se diferenciaron los roles que generan solicitudes, los que autorizan o validan, los que gestionan y acompañan, y aquellos que participan como proveedores externos o instancias de control. A través de las conexiones entre ellos se representa el flujo completo de la información y de las responsabilidades, resaltando la interacción continua entre áreas internas y externas que intervienen en el ciclo de adquisición.
- **Cómo representa las necesidades del cliente:** El modelo refleja de manera clara cómo las unidades solicitantes pueden iniciar y hacer seguimiento a sus solicitudes, cómo los decanos/directores aprueban presupuestos, cómo la Jefatura de Adquisiciones coordina y controla el proceso, y cómo participan actores externos como proveedores e INSPEKTOR. Con esto, se abordan las principales necesidades del cliente: trazabilidad, control financiero y cumplimiento normativo.
- **Qué supuestos se tomaron:** Se asumió que el SIGA y el Portal de Servicios se representan como un único sistema en el C1, para no sobrecargar el diagrama con detalles técnicos.
Se consideró que todos los procesos pasan de alguna forma por la Jefatura de Adquisiciones, aun cuando en la práctica puedan existir diferentes niveles de autonomía.

## 📈 Diagrama final entregado
### Vista de contexto

![c1-final-diagram](c1-contexto-final.png)

### Vista de contenedores

![c2-final-diagram](c2-contenedores-final.png)

## 📋 Tabla de actores, entidades o componentes (si aplica)

| Nombre del elemento | Tipo | Descripción | Responsable |
|---------------------|------|-------------|-------------|
| Unidad solicitante  | Actor  | Dependencia académica o administrativa que identifica necesidades y registra solicitudes de adquisición. | Área solicitante |
| Decano / Director   | Actor  | Autoriza y valida presupuestalmente las solicitudes realizadas por la unidad. | Directivo de la unidad |
| Jefatura de adquisiciones | Actor | Coordina, valida y gestiona los procesos de compra o contratación. | Dirección de adquisiciones |
| Proveedores externos | Actor | Empresas o personas que ofertan bienes o servicios y cumplen las órdenes de compra. | Contratista |
| Comité / Subcomisión de adquisiciones | Actor | Instancia de control y decisión que revisa planes, indicadores y políticas del proceso. | Gobierno institucional |
| (SIGA + Portal) | Sistema | Plataforma que integra el registro, validación y trazabilidad de las solicitudes y procesos de adquisición. | Área de sistemas / financiera |
| Plataforma INSPEKTOR | Sistema externo | Herramienta de validación legal y revisión de listas restrictivas de proveedores. | Área jurídica / cumplimiento |

## 🔍 Investigación complementaria
### Tema investigado:
(Ej: Buenas prácticas BPMN, comparación TOGAF vs C4, principios de seguridad STRIDE, etc.)

### Resumen:
Describa en 2–3 párrafos lo investigado, citando fuentes cuando sea necesario. Incluya cómo se relaciona con el taller.

## 📚 Referencias
- [1] Apellido, Nombre. *Título*. Año. URL o DOI.
- [2] Fuente oficial BPMN: https://www.omg.org/spec/BPMN/

---

_Este documento hace parte de la entrega del taller X del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._
