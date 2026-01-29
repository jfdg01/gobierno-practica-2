# Dominio DSS: Entregar, Dar Servicio y Soporte
**Dominio de Gestión de COBIT 2019 · 6 Procesos**

---

## Diapositiva 1: Introducción al Dominio DSS

El dominio DSS (Entregar, Dar Servicio y Soporte) es el corazón de las operaciones de TI en COBIT 2019. Mientras que BAI construye las soluciones, DSS las opera día a día, asegurando que los servicios tecnológicos funcionen correctamente y satisfagan las necesidades de los usuarios. Este dominio es fundamental para mantener la continuidad del negocio y la satisfacción de los usuarios finales con los servicios de TI.

### Componentes Clave

*   **Operaciones:** Gestión diaria de la infraestructura y servicios de TI, incluyendo monitorización, mantenimiento preventivo y ejecución de procedimientos operativos estándar.
*   **Soporte:** Atención a usuarios mediante gestión de peticiones, incidentes y problemas, proporcionando respuestas rápidas y efectivas a las necesidades del negocio.
*   **Seguridad y Continuidad:** Protección de los activos de información y garantía de que los servicios críticos puedan recuperarse ante incidentes graves o desastres.

### Los 6 Procesos del Dominio DSS
El dominio DSS se estructura en seis procesos complementarios: 
*   **DSS01** gestiona las operaciones diarias.
*   **DSS02** atiende peticiones e incidentes.
*   **DSS03** analiza y resuelve problemas de raíz.
*   **DSS04** asegura la continuidad del negocio.
*   **DSS05** protege los servicios mediante controles de seguridad.
*   **DSS06** supervisa los controles de los procesos de negocio.

Juntos, estos procesos garantizan que los servicios de TI sean fiables, seguros y respondan a las necesidades de los usuarios.

> **Aplicación en el Contexto Universitario**
>
> En la Universidad de Jaén, el dominio DSS se activa una vez que la plataforma de gestión de TFM está en producción. Abarca desde la monitorización diaria del sistema para detectar problemas antes de que afecten a los usuarios, pasando por la atención a consultas e incidencias de estudiantes y tutores, hasta la garantía de que el sistema esté disponible durante los períodos críticos de entrega y defensa de trabajos. DSS asegura que la inversión realizada en BAI genere valor continuo.

---

## Diapositiva 2: DSS01: Gestionar Operaciones

El proceso DSS01 es el motor que mantiene en funcionamiento los servicios de TI. Se encarga de coordinar y ejecutar las actividades operativas necesarias para entregar los servicios acordados, incluyendo la monitorización de la infraestructura, la ejecución de procedimientos programados y la respuesta a eventos operativos. Una gestión de operaciones eficaz es invisible para los usuarios: todo simplemente funciona.

### Prácticas Clave

*   **DSS01.01 - Realizar procedimientos operativos:** Ejecutar los procedimientos operativos estándar de forma consistente y documentada, incluyendo trabajos programados, copias de seguridad, arranques y paradas de sistemas, y tareas de mantenimiento rutinario.
*   **DSS01.02 - Gestionar servicios externalizados de TI:** Supervisar el rendimiento de los proveedores de servicios externos, verificando el cumplimiento de los acuerdos de nivel de servicio y gestionando la comunicación y escalado cuando sea necesario.
*   **DSS01.03 - Monitorizar la infraestructura de TI:** Vigilar continuamente el estado de los sistemas, redes y aplicaciones mediante herramientas de monitorización, detectando anomalías y eventos que requieran atención antes de que impacten a los usuarios.
*   **DSS01.04 - Gestionar el entorno físico:** Mantener las condiciones ambientales adecuadas para los equipos de TI, incluyendo climatización, alimentación eléctrica, control de acceso físico y protección contra incendios e inundaciones.
*   **DSS01.05 - Gestionar las instalaciones:** Administrar el centro de datos y las instalaciones de TI, planificando la capacidad física, gestionando el cableado y asegurando la disponibilidad de los recursos de infraestructura.

> **Ejemplo TFM: Gestión de Operaciones**
>
> Para la plataforma de TFM, DSS01 implica: ejecutar copias de seguridad diarias de la base de datos a las 3:00 AM, monitorizar el uso de CPU y memoria de los servidores con alertas automáticas si superan el 80%, verificar mensualmente que el proveedor de firma electrónica cumple el SLA de disponibilidad del 99.9%, y supervisar las condiciones del centro de datos universitario donde están alojados los servidores. Durante los períodos de defensa de TFM (junio-julio), se incrementa la monitorización para detectar cualquier degradación del rendimiento.

---

## Diapositiva 3: DSS02: Gestionar Peticiones de Servicio e Incidentes

El proceso DSS02 es la cara visible del departamento de TI ante los usuarios. Gestiona todas las comunicaciones con los usuarios, tanto las peticiones de servicio (solicitudes planificadas) como los incidentes (interrupciones no planificadas). Un proceso de gestión de incidentes eficaz minimiza el impacto de las interrupciones y restaura el servicio normal lo más rápidamente posible.

### Prácticas Clave

*   **DSS02.01 - Definir esquemas de clasificación de incidentes y peticiones:** Establecer categorías, prioridades y niveles de urgencia e impacto que permitan gestionar eficientemente el flujo de trabajo y asignar recursos adecuadamente según la criticidad.
*   **DSS02.02 - Registrar, clasificar y priorizar peticiones e incidentes:** Capturar toda la información relevante de cada caso, asignar la categoría correcta y determinar la prioridad de atención basándose en el impacto al negocio y la urgencia.
*   **DSS02.03 - Verificar, aprobar y resolver peticiones:** Procesar las peticiones de servicio según los procedimientos establecidos, verificando la autorización necesaria y ejecutando las acciones requeridas dentro de los plazos acordados.
*   **DSS02.04 - Investigar, diagnosticar y asignar incidentes:** Analizar los síntomas del incidente, identificar la causa inmediata y escalar al grupo de soporte adecuado cuando sea necesario para su resolución.
*   **DSS02.05 - Resolver y recuperarse de incidentes:** Aplicar las soluciones o workarounds necesarios para restaurar el servicio, documentar las acciones realizadas y confirmar con el usuario que el servicio ha sido restablecido.
*   **DSS02.06 - Cerrar peticiones e incidentes:** Verificar la satisfacción del usuario, completar la documentación del caso y actualizar la base de conocimiento con las soluciones aplicadas para facilitar futuras resoluciones.

> **Ejemplo TFM: Peticiones e Incidentes**
>
> DSS02 gestiona situaciones como: un estudiante solicita restablecer su contraseña (petición de prioridad baja, resolución en 4 horas), un coordinador no puede acceder a las rúbricas de evaluación (incidente de prioridad media, resolución en 2 horas), o el sistema de firma electrónica falla durante la firma de actas (incidente crítico, resolución inmediata con escalado al proveedor). Cada caso se registra en el sistema de tickets, se clasifica según impacto y urgencia, se asigna al técnico adecuado, y se cierra verificando la satisfacción del usuario.

---

## Diapositiva 4: DSS03: Gestionar Problemas

El proceso DSS03 va más allá de la resolución reactiva de incidentes para identificar y eliminar las causas raíz de los problemas recurrentes. Mientras que DSS02 se centra en restaurar el servicio rápidamente, DSS03 investiga por qué ocurren los incidentes y trabaja para evitar que se repitan. Esta aproximación proactiva reduce el volumen de incidentes y mejora la estabilidad general de los servicios.

### Prácticas Clave

*   **DSS03.01 - Identificar y clasificar problemas:** Detectar problemas a partir del análisis de tendencias en incidentes, alertas de monitorización o reportes de usuarios. Clasificar los problemas según su impacto potencial y área afectada.
*   **DSS03.02 - Investigar y diagnosticar problemas:** Realizar análisis de causa raíz utilizando técnicas como los 5 porqués, diagramas de Ishikawa o análisis de Pareto para identificar el origen real del problema.
*   **DSS03.03 - Levantar errores conocidos:** Documentar los problemas investigados como errores conocidos, incluyendo sus síntomas, causa raíz identificada y soluciones temporales (workarounds) disponibles.
*   **DSS03.04 - Resolver y cerrar problemas:** Implementar soluciones definitivas coordinando con BAI06 (gestión de cambios), verificar la efectividad de la solución y cerrar el registro del problema con toda la documentación.
*   **DSS03.05 - Realizar gestión proactiva de problemas:** Anticipar problemas potenciales mediante análisis de tendencias, revisiones de capacidad y evaluación de riesgos operativos antes de que generen incidentes.

> **Ejemplo TFM: Gestión de Problemas**
>
> DSS03 analiza patrones como: múltiples incidentes de lentitud reportados los viernes a última hora se investigan y se descubre que coinciden con el backup semanal completo; la causa raíz es que el backup consume excesivos recursos de I/O. Se documenta como error conocido con workaround temporal (avisar a usuarios de posible lentitud) y se planifica solución definitiva (mover backup a horario nocturno). Proactivamente, antes del período de defensas se revisan tendencias de carga para anticipar posibles cuellos de botella.

---

## Diapositiva 5: DSS04: Gestionar la Continuidad

El proceso DSS04 prepara a la organización para sobrevivir a interrupciones graves que van más allá de los incidentes cotidianos. Incluye la planificación ante desastres, la definición de estrategias de recuperación y la realización de pruebas periódicas para verificar que los planes funcionan. Un buen plan de continuidad puede marcar la diferencia entre una interrupción temporal y una crisis organizacional.

### Prácticas Clave

*   **DSS04.01 - Definir la política y el alcance de continuidad del negocio:** Establecer el marco de trabajo para la continuidad, identificando los servicios críticos, los requisitos de tiempo de recuperación (RTO) y punto de recuperación (RPO) aceptables.
*   **DSS04.02 - Mantener una estrategia de continuidad:** Definir las estrategias y opciones de recuperación para cada servicio crítico, incluyendo sitios alternativos, redundancia de sistemas y acuerdos con proveedores de recuperación.
*   **DSS04.03 - Desarrollar e implementar planes de continuidad:** Documentar los procedimientos detallados de respuesta y recuperación, incluyendo roles, responsabilidades, secuencias de activación y listas de contactos de emergencia.
*   **DSS04.04 - Ejercitar, probar y revisar los planes:** Realizar pruebas periódicas de los planes mediante simulacros, ejercicios de mesa o pruebas técnicas reales para verificar su efectividad y actualidad.
*   **DSS04.05 - Revisar, mantener y mejorar los planes:** Actualizar los planes tras cambios significativos en el entorno, resultados de pruebas o lecciones aprendidas de incidentes reales.
*   **DSS04.06 - Realizar formación en el plan de continuidad:** Capacitar al personal involucrado en la respuesta a emergencias, asegurando que conocen sus roles y pueden ejecutar los procedimientos cuando sea necesario.
*   **DSS04.07 - Gestionar los acuerdos de respaldo:** Mantener contratos y acuerdos con proveedores de servicios de recuperación, sitios alternativos y otros recursos necesarios para la continuidad.

> **Ejemplo TFM: Continuidad del Servicio**
>
> DSS04 establece que la plataforma de TFM es crítica durante convocatorias de defensa (junio-julio, septiembre). Se define RTO de 4 horas (tiempo máximo de interrupción) y RPO de 1 hora (máxima pérdida de datos aceptable). La estrategia incluye: réplica de base de datos en tiempo real a servidor secundario, backups cada hora durante períodos críticos, y procedimiento documentado de failover. Anualmente se realiza un simulacro de recuperación completa, verificando que el sistema puede restaurarse en menos de 4 horas. El personal de guardia conoce los procedimientos de activación.

---

## Diapositiva 6: DSS05: Gestionar Servicios de Seguridad

El proceso DSS05 protege los activos de información de la organización implementando y operando los controles de seguridad definidos en las políticas. Mientras que APO13 define la estrategia de seguridad, DSS05 la ejecuta día a día, protegiendo sistemas, redes, endpoints y datos contra amenazas internas y externas.

### Prácticas Clave

*   **DSS05.01 - Proteger contra software malicioso:** Implementar y mantener soluciones antimalware en todos los endpoints y servidores, gestionar actualizaciones de firmas y responder a detecciones de malware.
*   **DSS05.02 - Gestionar la seguridad de la red y las conexiones:** Configurar y mantener firewalls, sistemas de detección de intrusiones, segmentación de red y conexiones seguras (VPN) para proteger el perímetro y las comunicaciones.
*   **DSS05.03 - Gestionar la seguridad de los endpoints:** Asegurar los dispositivos de usuario mediante configuraciones seguras, cifrado, gestión de parches y políticas de uso aceptable.
*   **DSS05.04 - Gestionar la identidad del usuario y el acceso lógico:** Administrar cuentas de usuario, permisos y autenticación, asegurando que cada usuario tenga acceso solo a los recursos necesarios para su función.
*   **DSS05.05 - Gestionar el acceso físico a los activos de TI:** Controlar el acceso físico a centros de datos, salas de servidores y equipos críticos mediante tarjetas de acceso, videovigilancia y registros de entrada.
*   **DSS05.06 - Gestionar documentos sensibles y dispositivos de salida:** Proteger la información en formato físico, controlando impresoras, destrucción segura de documentos y gestión de medios extraíbles.
*   **DSS05.07 - Monitorizar la infraestructura para eventos de seguridad:** Recopilar y analizar logs de seguridad, detectar actividad sospechosa y responder a alertas mediante un proceso de gestión de eventos de seguridad.

> **Ejemplo TFM: Seguridad Operativa**
>
> DSS05 protege la plataforma de TFM mediante: autenticación integrada con el directorio LDAP universitario y doble factor para administradores, cifrado TLS en todas las conexiones, control de acceso basado en roles (estudiante solo ve sus TFM, tutor ve los que dirige, coordinador ve todos de su máster), firewall de aplicación web (WAF) para proteger contra ataques comunes, y monitorización de logs para detectar intentos de acceso no autorizado. Los TFM subidos se analizan automáticamente con antimalware antes de almacenarlos.

---

## Diapositiva 7: DSS06: Gestionar Controles de Procesos de Negocio

El proceso DSS06 asegura que los procesos de negocio soportados por TI incluyan los controles necesarios para garantizar la integridad, exactitud y validez de la información. Este proceso es especialmente relevante para sistemas que procesan transacciones críticas o datos sensibles, donde errores o manipulaciones podrían tener consecuencias significativas.

### Prácticas Clave

*   **DSS06.01 - Alinear las actividades de control con los objetivos de negocio:** Identificar los procesos de negocio críticos y definir los controles necesarios para asegurar que los sistemas de información los soporten adecuadamente, manteniendo la integridad de los datos.
*   **DSS06.02 - Controlar el procesamiento de la información:** Implementar controles de validación de entrada, procesamiento y salida que aseguren la exactitud, completitud y autorización de las transacciones procesadas por los sistemas.
*   **DSS06.03 - Gestionar roles, responsabilidades y derechos de acceso:** Asegurar la segregación de funciones adecuada en los procesos de negocio, evitando que una misma persona pueda realizar acciones incompatibles sin supervisión.
*   **DSS06.04 - Gestionar errores y excepciones:** Establecer procedimientos para detectar, registrar, investigar y corregir errores de procesamiento, asegurando que las excepciones se resuelvan de forma controlada.
*   **DSS06.05 - Asegurar la trazabilidad y rendición de cuentas de eventos:** Mantener registros de auditoría que permitan reconstruir la secuencia de eventos, identificar quién hizo qué y cuándo, y demostrar el cumplimiento de políticas y regulaciones.
*   **DSS06.06 - Asegurar los activos de información:** Proteger la información procesada por los sistemas de negocio mediante controles de acceso, cifrado y procedimientos de manejo seguro durante todo su ciclo de vida.

> **Ejemplo TFM: Controles de Procesos**
>
> DSS06 implementa controles críticos en la gestión de TFM: validación de que las calificaciones están en rango válido (0-10) antes de grabar, segregación de funciones (el tutor propone calificación, pero solo el tribunal puede aprobarla oficialmente), registro de auditoría de todas las acciones sobre actas con timestamp y usuario, control de que un TFM no puede pasar a estado "defendido" sin todos los campos obligatorios completos, y verificación de que las firmas electrónicas corresponden a los miembros del tribunal asignados. Cualquier error o excepción genera una alerta al coordinador para su revisión.

---

## Diapositiva 8: Caso Práctico: DSS Aplicado a la Gestión de TFM

Veamos cómo los 6 procesos del dominio DSS trabajan conjuntamente para mantener operativa la plataforma de gestión de Trabajos Fin de Máster, garantizando un servicio fiable, seguro y con capacidad de recuperación ante incidentes.

### Componentes del Caso Práctico

*   **Operaciones Diarias (DSS01):** Monitorización 24/7 con alertas automáticas, backups diarios a las 3:00 AM con verificación, revisión semanal de rendimiento, y mantenimiento preventivo mensual de base de datos. Durante convocatorias: monitorización reforzada cada 15 minutos.
*   **Soporte a Usuarios (DSS02):** Service Desk disponible de 8:00 a 20:00 en días laborables, sistema de tickets con SLA por prioridad (crítico: 1h, alto: 4h, medio: 8h, bajo: 24h), base de conocimiento con 89 artículos de autoayuda, y encuesta de satisfacción tras cada cierre.
*   **Gestión de Problemas (DSS03):** Reunión mensual de análisis de tendencias, 12 errores conocidos documentados con workarounds, análisis de causa raíz para incidentes que se repiten más de 3 veces, y revisión proactiva antes de cada convocatoria de defensas.
*   **Continuidad (DSS04):** RTO: 4 horas, RPO: 1 hora. Réplica síncrona a servidor secundario, procedimiento de failover documentado y probado, simulacro anual de recuperación completa, y equipo de respuesta con contactos de emergencia 24/7.
*   **Seguridad (DSS05):** Autenticación LDAP + MFA para administradores, cifrado TLS 1.3, WAF activo, control de acceso por roles, escaneo antimalware de archivos subidos, y revisión trimestral de logs de seguridad. Cumplimiento ENS nivel medio.
*   **Controles de Proceso (DSS06):** Validación de calificaciones (0-10), segregación tutor/tribunal, pista de auditoría completa, control de estados de workflow, verificación de firmas electrónicas, y alertas automáticas de excepciones al coordinador.

> **Métricas de Servicio (Último Curso Académico)**
>
> Disponibilidad del servicio: 99.7% (objetivo: 99.5%). Tiempo medio de resolución de incidentes: 2.3 horas. Incidentes críticos: 2 (ambos resueltos en menos de 1 hora). Satisfacción de usuarios: 4.4/5. Problemas resueltos definitivamente: 8. Simulacro de recuperación: exitoso en 3.2 horas (objetivo: 4 horas). Intentos de acceso no autorizado detectados y bloqueados: 47.

---

## Diapositiva 9: Resumen del Dominio DSS

El dominio DSS es donde la tecnología entrega valor real al negocio día a día. Todo el trabajo de planificación (APO) y construcción (BAI) cobra sentido cuando los servicios funcionan correctamente, los usuarios están satisfechos y la organización puede confiar en su tecnología. DSS es el dominio más visible para los usuarios finales y el que más directamente impacta en su percepción de TI.

### Puntos Clave

*   **Operaciones (DSS01):** El motor silencioso que mantiene todo funcionando: monitorización, backups, mantenimiento preventivo y gestión de la infraestructura día a día.
*   **Soporte Reactivo (DSS02-03):** **DSS02** restaura el servicio rápidamente ante incidentes. **DSS03** elimina las causas raíz para evitar recurrencia.
*   **Protección (DSS04-05-06):** **DSS04** garantiza recuperación ante desastres. **DSS05** protege contra amenazas. **DSS06** asegura integridad de procesos.

### Conexión con Otros Dominios
DSS recibe de **BAI** las soluciones listas para operar, junto con documentación y configuración. Implementa las políticas de seguridad definidas en **APO13** y los controles establecidos por **EDM03**. Proporciona a **MEA** información sobre incidentes, disponibilidad y cumplimiento para su monitorización. DSS es el ejecutor final de todo el ciclo de valor de TI: convierte la tecnología en servicio.

> **Claves para el Éxito en DSS**
>
> Para maximizar el valor del dominio DSS: invierte en monitorización proactiva para detectar problemas antes de que los usuarios los sufran, documenta los errores conocidos y sus workarounds para acelerar la resolución, prueba regularmente los planes de continuidad (un plan no probado es solo un documento), automatiza los controles de seguridad y proceso para reducir errores humanos, y mide constantemente la satisfacción del usuario como indicador principal de éxito. El mejor servicio de TI es el que los usuarios no notan porque simplemente funciona.
