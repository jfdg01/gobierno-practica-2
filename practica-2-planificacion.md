# **Dominio APO \- Planificación**

**Responsable de Planificación**: Javier Francisco Dibo Gómez   
**Procesos Asignados**: 

* APO02 (Gestionar la Estrategia),   
* APO12 (Gestionar el Riesgo),   
* APO13 (Gestionar la Seguridad)

  ## **Introducción al Dominio APO en Seguros Plus**

El dominio de Alineación, Planificación y Organización (APO) es fundamental para transformar a Seguros Plus de una organización con una TI reactiva y dispersa a una entidad impulsada por datos y procesos digitales seguros. Como Responsable de Planificación, el objetivo es establecer la dirección estratégica tecnológica, identificar y mitigar los riesgos críticos que amenazan el negocio (especialmente los relacionados con datos de salud) y blindar la organización con un marco de seguridad robusto.

Este dominio actúa como el puente traductor entre las **Metas de Negocio** (Crecimiento, Satisfacción, Eficiencia) y la **Ejecución Técnica**. Sin una estrategia clara (APO02), las inversiones del CFO carecerán de dirección; sin gestión de riesgos (APO12), la empresa navega a ciegas ante amenazas legales y operativas; y sin seguridad (APO13), la confianza del cliente —nuestro activo más valioso— es vulnerable.

## **APO02: Gestionar la Estrategia**

**Objetivo:** Alinear las capacidades de TI con los objetivos estratégicos de Seguros Plus para el periodo 2026-2028, pasando de un enfoque de soporte a uno de habilitador de negocio.

### **1\. Análisis del Contexto y Capacidades Actuales**

El diagnóstico revela una desconexión crítica. Mientras la Dirección busca digitalizar el 80% de los procesos y mejorar el NPS en un 20%, el área de TI opera con capacidades limitadas:

* **Brecha de Capacidad:** Equipo reducido (8 personas) enfocado en "apagar fuegos" (soporte reactivo) en lugar de innovación. **Se identifica una necesidad crítica de adquirir nuevas competencias (upskilling) para soportar tecnologías Cloud/API, lo cual deberá ser abordado en el plan de capacitación (BAI05).**  
* **Brecha Tecnológica:** Sistemas "isla" (CRM, Siniestros, Ventas) que no se hablan, forzando la manualidad.  
* **Brecha de Percepción:** TI es vista como un centro de coste, no de inversión.

  ### **2\. Definición de la Estrategia TI (Roadmap 2026-2028)**

Para cerrar estas brechas, se define una estrategia basada en tres pilares, alineada con las restricciones presupuestarias del CFO y las necesidades operativas:

#### **Integración y Dato Único**

* **Objetivo de Negocio:** Agilidad en Siniestros (15 a 5 días) y Eficiencia Interna  
* **Iniciativas Clave de TI:**  
  * Implementación de **Integración vía APIs ligeras** (Middleware) entre CRM y Siniestros, priorizando bajo mantenimiento (OpEx) para el equipo actual. *Esta arquitectura será detallada en los requisitos técnicos del dominio BAI (BAI02).*  
  * Eliminación de bases de datos locales (Excel) y centralización en Data Warehouse.

  #### **Experiencia Digital Segura**

* **Objetivo de Negocio:** Incremento de Satisfacción (NPS)  
* **Iniciativas Clave de TI:**  
  * Refactorización del Portal de Clientes (UX/UI).  
  * Implementación de Firma Digital legalmente vinculante.

  #### **Eficiencia y Sostenibilidad**

* **Objetivo de Negocio:** Sostenibilidad Financiera (Reducción de OpEx)  
* **Iniciativas Clave de TI:**  
  * Migración a arquitectura Cloud (AWS) para flexibilizar costes.  
  * Automatización de procesos repetitivos (RPA) para liberar al personal de tareas manuales.

  ### **3\. Modelo de Priorización de Inversiones**

Para asegurar la alineación con el principio de "Calidad del Gasto" del CFO, toda iniciativa estratégica debe pasar por un filtro de priorización:

1. **Cumplimiento Normativo (Protección de Valor):** Proyectos requeridos por ley (ej. GDPR). Prioridad Máxima para **mitigar Pasivos Contingentes** (multas financieras) y blindar la caja de la empresa.  
2. **Continuidad de Negocio:** Actualización de sistemas obsoletos que amenazan la operación.  
3. **Retorno de Inversión (ROI):** Proyectos que generan ahorro directo o ingresos (ej. Automatización).  
4. **Innovación:** Apuestas a futuro (ej. IA para análisis de siniestros).

   ## **APO12: Gestionar el Riesgo**

**Objetivo:** Identificar, evaluar y reducir los riesgos relacionados con TI dentro de niveles de tolerancia aceptables, protegiendo la reputación y la estabilidad de Seguros Plus.

### **1\. Perfil de Riesgo de Seguros Plus**

La organización maneja datos de Categoría Especial (Salud) según el RGPD, lo que eleva nuestro perfil de riesgo a **ALTO**. La combinación de datos sensibles, sistemas obsoletos y procesos manuales crea una "tormenta perfecta" para incidentes graves.

### **2\. Registro y Evaluación de Riesgos (Risk Heatmap)**

Se han identificado los siguientes riesgos prioritarios, evaluados por Probabilidad (1-5) e Impacto (1-5):

#### **R-01 Fuga de Información de Salud**

* **Descripción:** Exposición de datos médicos de clientes debido al uso de canales inseguros (Excel compartidos, Emails sin cifrar).  
* **Evaluación:** Probabilidad 4 (Alto) x Impacto 5 (Crítico) \= **Nivel 20 (Extremo)**  
* **Dueño:** CIO / DPO

  #### **R-02 Shadow IT / Desgobierno**

* **Descripción:** Contratación de software por departamentos (Ventas/Marketing) sin validación de seguridad ni integración, creando silos y vulnerabilidades.  
* **Evaluación:** Probabilidad 5 (Muy Alto) x Impacto 3 (Medio) \= **Nivel 15 (Alto)**  
* **Dueño:** CFO / CIO

  ### **R-03 Interrupción del Servicio (Downtime)**

* **Descripción:** Caída de sistemas críticos (Siniestros/CRM) por infraestructura obsoleta o falta de redundancia, paralizando la atención.  
* **Evaluación:** Probabilidad 3 (Medio) x Impacto 4 (Alto) \= **Nivel 12 (Alto)**  
* **Dueño:** Resp. Operaciones

  #### **R-04 Dependencia de Personal Clave**

* **Descripción:** Pérdida de conocimiento crítico si uno de los 8 técnicos abandona la empresa (Bus Factor \= 1).  
* **Evaluación:** Probabilidad 3 (Medio) x Impacto 3 (Medio) \= **Nivel 9 (Medio)**  
* **Dueño:** RRHH / CIO

  #### **R-05 Incumplimiento Normativo (GDPR)**

* **Descripción:** Sanciones económicas (hasta 4% facturación) por no garantizar derechos ARCO o trazabilidad de datos.  
* **Evaluación:** Probabilidad 2 (Bajo) x Impacto 5 (Crítico) \= **Nivel 10 (Alto)**  
* **Dueño:** Asesoría Legal

  ### **3\. Plan de Tratamiento de Riesgos**

* **Para R-01 y R-05 (Datos):** Estrategia de **Mitigación**. Implementación inmediata de controles de DLP (Data Loss Prevention) y migración forzosa de datos locales a sistemas centrales seguros. (Ver APO13).  
* **Para R-02 (Shadow IT):** Estrategia de **Evitar/Controlar**. Implementación de la política de compras validada por el CFO. Bloqueo técnico de aplicaciones no autorizadas, acompañado de un proceso **"Fast-Track"** (aprobación en 48h) restringido exclusivamente a herramientas de **Bajo Riesgo** (sin tratamiento de datos personales). Si la herramienta implica datos de Nivel 4, requerirá validación completa de seguridad.  
* **Para R-03 (Downtime):** Estrategia de **Transferir/Mitigar**. Migración a la nube (SLA garantizado por proveedor) y establecimiento de planes de recuperación (DRP).

  ## **APO13: Gestionar la Seguridad**

**Objetivo:** Definir, operar y monitorizar un Sistema de Gestión de Seguridad de la Información (SGSI) que garantice la Confidencialidad, Integridad y Disponibilidad de los datos de Seguros Plus.

### **1\. Marco de Gestión de Seguridad**

Dado el tamaño de la empresa, no buscaremos una certificación ISO 27001 completa a corto plazo, pero sí alinearemos nuestros controles a sus dominios, enfocándonos en la protección de datos personales.

### **2\. Políticas de Seguridad Clave**

Se definen tres políticas mandatorias que todos los empleados (desde agentes hasta directivos) deben cumplir:

#### **A. Política de Clasificación y Manejo de la Información**

Se establecen niveles de confidencialidad para etiquetar todos los documentos y datos:

* **Nivel 1: Público:** Información corporativa general (Web, Marketing).  
* **Nivel 2: Interno:** Procedimientos, directorios, comunicaciones internas.  
* **Nivel 3: Confidencial (Restringido):** Datos financieros, estrategias, contraseñas.  
* **Nivel 4: Datos Sensibles (Crítico):** **Historiales médicos, diagnósticos, datos de siniestros de salud.**  
  * *Control:* Los datos de Nivel 4 **NUNCA** pueden residir en equipos locales, USBs o enviarse por correo sin cifrado. Deben estar siempre en el CRM/Sistema Core.  
  * *Medida de Transición:* Dado que actualmente existen datos en Excel (Riesgo R-01), se establece una medida transitoria de **cifrado de archivos individuales** y borrado seguro tras su migración al CRM, responsabilidad que recaerá en Operaciones (DSS01) bajo supervisión de cumplimiento (MEA03).

  #### **B. Política de Control de Acceso (RBAC)**

Se elimina el acceso genérico. El acceso a la información se basará en el principio de "mínimo privilegio" según el rol:

* **Agentes Comerciales:** Acceso solo a datos de contacto y pólizas de *sus* clientes. No acceden a historial médico detallado salvo en apertura de siniestro.  
* **Tramitadores de Siniestros:** Acceso completo al expediente médico necesario para la gestión. Trazabilidad total de quién vio qué dato y cuándo (Logs de acceso).  
* **TI:** Acceso de administración, pero sin visibilidad de los datos sensibles (base de datos cifrada).

  #### **C. Política de Seguridad en el Puesto de Trabajo y Movilidad**

Considerando el modelo híbrido (agentes en calle, teletrabajo):

* **Cifrado de Dispositivos:** Todos los portátiles y móviles corporativos deben tener el disco cifrado (BitLocker/FileVault).  
* **Autenticación Robusta:** Implementación de **MFA (Autenticación de Multifactor)** obligatoria para acceder a sistemas corporativos desde fuera de la oficina.  
* **Gestión de Vulnerabilidades:** Actualización automática de parches de seguridad en todos los equipos (evitar el "ya lo actualizaré mañana").

  ### **3\. Integración con otros Dominios**

* **Con BAI (Implementación):** La seguridad debe incorporarse desde el diseño (**Security by Design**). Cualquier nuevo desarrollo (ej. el nuevo Portal de Clientes) debe pasar pruebas de seguridad (análisis de vulnerabilidades) antes de salir a producción.  
* **Con DSS (Operaciones):** Se define el **Plan de Respuesta ante Incidentes**. Este protocolo será ejecutado operativamente por el equipo de **DSS02 (Gestión de Incidentes)**. Si Operaciones detecta una anomalía (ej. ransomware), debe existir un protocolo claro de contención, erradicación y notificación a la AEPD (Agencia Española de Protección de Datos) en menos de 72h si afecta a datos personales.

  ### **Resumen de Valor del Rol de Planificación**

La labor realizada en este dominio sienta las bases para el éxito del proyecto. Hemos definido **HACIA DÓNDE** vamos (Estrategia alineada con un ROI claro), **QUÉ PELIGROS** enfrentamos en el camino (Mapa de Riesgos enfocado en datos de salud) y **CÓMO NOS PROTEGEMOS** (Políticas de Seguridad y Control de Accesos). Esto permite al Responsable de Implementación construir sistemas sólidos y al Responsable de Operaciones dormir tranquilo sabiendo que los riesgos están controlados.