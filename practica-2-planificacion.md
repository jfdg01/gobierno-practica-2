# **Dominio APO – Planificación: Plataforma ITSM de Seguros Plus**

**Responsable de Planificación**: Javier Francisco Dibo Gómez  
**Procesos Asignados**: APO02 (Gestionar la Estrategia), APO12 (Gestionar el Riesgo), APO13 (Gestionar la Seguridad)


## **Introducción al Sistema ITSM en Seguros Plus**

La plataforma de Gestión de Servicios de TI (ITSM) representa una pieza fundamental en la transformación digital de Seguros Plus. Actualmente, la organización carece de una herramienta formal para gestionar incidencias y solicitudes: los reportes de fallos llegan de forma desordenada por correo electrónico o llamadas directas, y el seguimiento se realiza en hojas de cálculo, lo que impide tener trazabilidad, métricas de rendimiento o una base de conocimientos para evitar problemas recurrentes.

El dominio APO establece las bases estratégicas para la implementación exitosa del ITSM, asegurando su alineación con los objetivos de negocio (eficiencia operativa, reducción de tiempos de respuesta), identificando los riesgos específicos del proyecto y definiendo los controles de seguridad necesarios para proteger la información gestionada a través de la plataforma.


## **APO02: Gestionar la Estrategia del ITSM**

**Objetivo:** Alinear la implementación del sistema ITSM con los objetivos estratégicos de Seguros Plus, transformando el soporte reactivo actual en un servicio proactivo y medible.

### **1. Análisis del Contexto Actual**

El diagnóstico revela una situación crítica en la gestión de servicios de TI:

- **Canales de entrada**: Correos, llamadas y mensajes informales sin un punto único de contacto (SPOC).
- **Registro de incidencias**: Hojas de cálculo Excel sin trazabilidad ni capacidad de auditoría.
- **Tiempos de resolución**: Desconocidos, ya que no se miden, lo que imposibilita establecer SLAs.
- **Base de conocimiento**: Inexistente, provocando que los problemas recurrentes no queden documentados.
- **Recursos**: 8 técnicos saturados dedicando el 80% de su tiempo a tareas reactivas de bajo valor.

### **2. Objetivos Estratégicos del ITSM**

La implementación del ITSM soportará directamente las siguientes metas de negocio:

**Digitalización del 80% de los procesos**
- *Contribución del ITSM*: Automatización de flujos de soporte.  
- *KPI Objetivo*: 100% de incidencias gestionadas digitalmente.

**Satisfacción del cliente (+20% NPS)**
- *Contribución del ITSM*: Reducción de tiempos de respuesta.  
- *KPI Objetivo*: Resolución promedio inferior a 4 horas para incidencias de prioridad 2.

**Reducción de costes operativos (15%)**
- *Contribución del ITSM*: Liberación de técnicos para tareas de innovación.  
- *KPI Objetivo*: -30% de tiempo dedicado a tareas repetitivas.

**Capacitación del 100% del personal**
- *Contribución del ITSM*: Portal de autoservicio con base de conocimientos.  
- *KPI Objetivo*: 40% de incidencias resueltas mediante autoayuda.

### **3. Roadmap de Implementación (2026-2027)**

**Fase 1 – Fundamentos (Q1 2026):** Catálogo de servicios TI, definición de SLAs y selección de herramienta.

**Fase 2 – Despliegue Core (Q2-Q3 2026):** Puesta en marcha de la gestión de incidencias y peticiones, junto con el portal de usuarios.

**Fase 3 – Optimización (Q4 2026):** Implementación de la base de conocimientos, automatizaciones e integración con el CRM.

**Fase 4 – Madurez (2027):** Gestión de problemas, reporting avanzado y procesos de mejora continua.


## **APO12: Gestionar el Riesgo del ITSM**

**Objetivo:** Identificar, evaluar y definir respuestas para los riesgos asociados a la implementación y operación del sistema ITSM.

### **1. Perfil de Riesgo del Proyecto ITSM**

La implementación del ITSM gestiona información operativa crítica y afecta directamente la continuidad del negocio. Nivel de riesgo global: **MEDIO-ALTO**.

### **2. Registro de Riesgos**

**R-ITSM-01: Baja adopción por usuarios (resistencia al cambio)**
- Probabilidad: Alta (4) | Impacto: Alto (4) | **Nivel: 16 - Alto**
- Propietario: Directora de Operaciones

**R-ITSM-02: Fuga de información sensible vía tickets (datos de salud)**
- Probabilidad: Media (3) | Impacto: Crítico (5) | **Nivel: 15 - Alto**
- Propietario: CIO / DPO

**R-ITSM-03: Integración fallida con sistemas legacy (CRM, Siniestros)**
- Probabilidad: Media (3) | Impacto: Alto (4) | **Nivel: 12 - Alto**
- Propietario: CIO

**R-ITSM-04: Caída del ITSM paralizando la resolución de incidencias**
- Probabilidad: Baja (2) | Impacto: Alto (4) | **Nivel: 8 - Medio**
- Propietario: Responsable de Infraestructura

**R-ITSM-05: Sobrecostes por alcance descontrolado (scope creep)**
- Probabilidad: Media (3) | Impacto: Medio (3) | **Nivel: 9 - Medio**
- Propietario: CFO / CIO

**R-ITSM-06: Dependencia excesiva del proveedor (vendor lock-in)**
- Probabilidad: Baja (2) | Impacto: Medio (3) | **Nivel: 6 - Bajo**
- Propietario: CIO

### **3. Plan de Tratamiento de Riesgos**

**Para R-ITSM-01 (Baja adopción)** – Estrategia: Mitigar  
Se implementará un programa de embajadores digitales, formación gamificada, interfaz simplificada y comunicación de beneficios. Se priorizarán quick wins visibles en las primeras semanas.

**Para R-ITSM-02 (Fuga de datos sensibles)** – Estrategia: Mitigar  
Se establecerá clasificación automática de tickets sensibles, enmascaramiento de datos de salud, control de accesos por rol (ver APO13) y logs de auditoría.

**Para R-ITSM-03 (Integración fallida)** – Estrategia: Evitar/Mitigar  
Se seleccionará un ITSM con APIs REST abiertas, se desarrollarán conectores en Fase 1 y se realizarán pruebas de integración exhaustivas antes del go-live.

**Para R-ITSM-04 (Caída del servicio)** – Estrategia: Transferir  
Se contratará un servicio SaaS con SLA de 99.9% y se definirá un procedimiento manual de contingencia (fallback).

**Para R-ITSM-05 (Sobrecostes)** – Estrategia: Controlar  
Se aplicará gestión de cambios estricta (BAI06), Business Case validado por CFO y revisiones mensuales de alcance en el Comité Operativo.

**Para R-ITSM-06 (Vendor lock-in)** – Estrategia: Aceptar/Mitigar  
Se realizará exportación periódica de datos, documentación de configuraciones e inclusión de cláusulas contractuales de migración.


## **APO13: Gestionar la Seguridad del ITSM**

**Objetivo:** Definir los controles de seguridad necesarios para garantizar la confidencialidad, integridad y disponibilidad de la información gestionada a través del sistema ITSM.

### **1. Requisitos de Seguridad del ITSM**

El ITSM de Seguros Plus gestionará información que puede incluir referencias a datos de clientes (históricos de incidencias relacionadas con pólizas o siniestros), credenciales técnicas y configuraciones de sistemas críticos. Esto exige controles específicos alineados con el RGPD y las políticas internas de seguridad.

### **2. Políticas de Seguridad Aplicables al ITSM**

#### **A. Política de Control de Acceso (RBAC)**

El acceso al ITSM se basará en el principio de mínimo privilegio:

- **Usuario Final**: Puede crear tickets propios y consultar la base de conocimientos pública. No tiene acceso a tickets de otros usuarios ni a datos técnicos.

- **Agente de Soporte N1**: Puede gestionar tickets asignados y consultar la base de conocimientos interna. No tiene acceso a configuraciones ni a datos sensibles de clientes.

- **Agente de Soporte N2**: Tiene gestión avanzada y acceso a logs técnicos. Solo accede a datos de cliente en tickets escalados relacionados.

- **Administrador ITSM**: Tiene configuración completa del sistema pero sin visibilidad del contenido de tickets (solo estructura).

#### **B. Política de Clasificación de Información en Tickets**

- **Nivel Público**: Información de autoayuda (FAQs, guías de uso). Sin restricción de acceso.

- **Nivel Interno**: Incidencias operativas genéricas ("El CRM va lento"). Visible para agentes.

- **Nivel Confidencial**: Tickets con datos de negocio (configuraciones, credenciales). Solo accesible para N2+ con necesidad justificada.

- **Nivel Sensible**: Referencias a datos de salud ("Cliente X no puede acceder a su póliza de..."). Se aplica enmascaramiento automático y logs de acceso.

#### **C. Política de Auditoría y Trazabilidad**

- **Logging obligatorio**: Todas las acciones en el ITSM (creación, modificación, visualización de tickets) quedarán registradas.
- **Retención de logs**: Mínimo 2 años para cumplimiento RGPD.
- **Revisión trimestral**: Operaciones (DSS01) revisará accesos anómalos bajo supervisión de Cumplimiento (MEA03).

### **3. Controles Técnicos de Seguridad**

- **Autenticación MFA**: Obligatoria para acceso al ITSM desde fuera de la red corporativa. Responsable: Infraestructura TI.

- **Cifrado en tránsito**: TLS 1.3 para todas las comunicaciones. Responsable: Proveedor ITSM.

- **Cifrado en reposo**: Base de datos cifrada con AES-256. Responsable: Proveedor ITSM.

- **Timeout de sesión**: 15 minutos de inactividad para agentes, 5 minutos para administradores. Responsable: Configuración ITSM.

- **Anonimización**: Datos personales en tickets históricos anonimizados tras el cierre. Responsable: Automatización.

### **4. Integración con Otros Dominios**

- **Con BAI (Implementación):** La seguridad se incorporará desde el diseño del ITSM (*Security by Design*). Antes del despliegue, se realizarán pruebas de penetración y análisis de vulnerabilidades (BAI02).

- **Con DSS (Operaciones):** El ITSM incluirá un flujo específico para incidentes de seguridad que active el protocolo de respuesta definido en DSS02, incluyendo notificación a la AEPD si corresponde.

- **Con MEA (Monitorización):** Los indicadores del ITSM alimentarán el cuadro de mando de MEA01, y el cumplimiento de políticas de seguridad será verificado en MEA03.


## **Resumen Ejecutivo**

La implementación del sistema ITSM en Seguros Plus está estratégicamente alineada con los objetivos de transformación digital de la organización. Este documento establece:

1. **Estrategia (APO02)**: Un roadmap claro de implementación en 4 fases que conecta directamente con las metas de eficiencia, satisfacción y reducción de costes operativos.

2. **Gestión de Riesgos (APO12)**: Identificación de 6 riesgos críticos, siendo la resistencia al cambio y la protección de datos sensibles los de mayor prioridad, con planes de tratamiento concretos.

3. **Seguridad (APO13)**: Políticas de control de acceso basado en roles, clasificación de información y controles técnicos que garantizan el cumplimiento normativo (RGPD) y la protección de los datos gestionados.

Estas bases permiten al Responsable de Implementación (BAI) construir el sistema de forma segura y al Responsable de Operaciones (DSS) operarlo con métricas claras y riesgos controlados.