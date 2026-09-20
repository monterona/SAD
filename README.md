# Temporalización de Seguridad y Alta Disponibilidad

**Periodo:** 21 de septiembre de 2026–29 de enero de 2027  
**Horario:** lunes, sesiones de 3 horas  
**Total:** 14 sesiones y 42 horas  
**Centro:** Sevilla  
**Módulo:** Seguridad y Alta Disponibilidad — Código 0378

## Distribución general

| Unidad | Resultado de aprendizaje | Sesiones | Horas |
|---|---|---:|---:|
| 1. Fundamentos y pautas de seguridad | RA1 | 2 | 6 |
| 2. Mecanismos de seguridad activa | RA2 | 3 | 9 |
| 3. Acceso remoto y seguridad perimetral | RA3 | 2 | 6 |
| 4. Cortafuegos | RA4 | 1 | 3 |
| 5. Servidores proxy | RA5 | 2 | 6 |
| 6. Alta disponibilidad | RA6 | 3 | 9 |
| 7. Legislación y normas | RA7 | 1 | 3 |
| **Total** | **RA1–RA7** | **14** | **42** |

# [Anexo: relación entre índice, resultados de aprendizaje y criterios de evaluación](anexos/relacion_indice_ra_ce.md)

# Primer bloque: fundamentos y seguridad activa

## Sesión 1 — 21 de septiembre

**Unidad 1: Fundamentos y pautas de seguridad informática — RA1**

**Criterios de evaluación trabajados:** RA1.a, RA1.b, RA1.c, RA1.d y RA1.h.

- La información y los servicios como activos.
- Confidencialidad, integridad, disponibilidad, autenticidad y trazabilidad.
- Activos, amenazas, vulnerabilidades, riesgos y controles.
- Clasificación de amenazas físicas, lógicas y humanas.
- Introducción al análisis de riesgos.
- Clasificación de controles físicos, lógicos y organizativos.
- Funciones preventiva, detectiva, correctiva y recuperadora de los controles.

**Actividades prácticas:**

1. **Caso Clínica Sur:** inventario de al menos ocho activos y redacción de cuatro escenarios que relacionen amenaza, vulnerabilidad, activo e impacto.
2. **Matriz de riesgos:** valoración de la probabilidad y el impacto mediante una escala de 1 a 3, cálculo del nivel de riesgo y propuesta de tratamiento.
3. **Clasificación de controles:** identificación del tipo y la función principal de siete controles de seguridad.

**Evidencias evaluables:**

- Inventario con activo, responsable, objetivo de seguridad prioritario, dependencia y justificación.
- Cuatro escenarios de riesgo redactados de forma causal.
- Matriz priorizada con probabilidad, impacto, nivel y tratamiento propuesto.
- Clasificación razonada de controles físicos, lógicos u organizativos y de su función.

---

## Sesión 2 — 28 de septiembre

**Unidad 1: Fundamentos y pautas de seguridad informática — RA1**

**Criterios de evaluación trabajados:** RA1.e, RA1.f, RA1.g y RA1.i.

- Seguridad física y ambiental.
- Control de acceso físico y sistemas de alimentación ininterrumpida.
- Seguridad lógica, permisos y listas de control de acceso.
- Políticas de contraseñas y autenticación multifactor.
- Fundamentos de criptografía.
- Copias de seguridad, restauración y medios de almacenamiento.
- Funciones hash y comprobación de la integridad.
- Actuación inicial ante incidentes y análisis forense básico.
- Preservación de evidencias y cadena de custodia.

**Actividades prácticas:**

4. **Política de acceso:** redacción de ocho a diez reglas verificables sobre credenciales, autenticación multifactor, cuentas administrativas, recuperación y baja de usuarios.
5. **Integridad, copias y restauración:** cálculo y comparación de hashes SHA-256, modificación controlada de un archivo y comprobación de una restauración.
6. **Mini caso forense:** valoración de actuaciones ante un posible ransomware, propuesta de una secuencia inicial y cumplimentación de una cadena de custodia.

**Evidencias evaluables:**

- Política de acceso con reglas y justificaciones.
- Registro de hashes, interpretación de los resultados y evidencia de la restauración.
- Valoración razonada de las actuaciones del caso forense.
- Secuencia inicial de respuesta y ficha de cadena de custodia.

### Documentación de la unidad 1

- [Manual del alumnado](u1/SAD-unidad_1-manual_alumnado.md).
- [Resumen del alumnado](u1/SAD-unidad_1-resumen_alumnado.md).
- **Cuaderno de actividades del alumnado:** reúne las seis actividades anteriores, sin soluciones, con tablas, casillas y espacios para responder.
- **Guía docente y soluciones:** conserva la misma numeración, los productos entregables y la relación con los criterios de evaluación.

---

## Sesión 3 — 5 de octubre

**Unidad 2. Amenazas, ataques y software malicioso — RA2**

- Seguridad activa y pasiva.
- Clasificación de los ataques.
- Ingeniería social.
- Virus, gusanos, troyanos, ransomware, spyware y puertas traseras.
- Anatomía y ciclo de vida de un ataque.
- Indicadores de compromiso.

**Actividad práctica:**

Análisis guiado de un incidente de ransomware en un entorno simulado.

**Evidencia evaluable:**

Ficha de análisis con vector de entrada, comportamiento, impacto y contramedidas.

---

## Sesión 4 — 19 de octubre

**Unidad 2. Bastionado y protección de equipos — RA2**

- Verificación del origen y autenticidad del software.
- Gestión de actualizaciones y parches.
- Reducción de servicios y puertos expuestos.
- Configuración segura de usuarios, permisos y privilegios.
- Antivirus, antimalware y protección del punto final.
- Cifrado de datos y certificados digitales.

**Actividad práctica:**

Bastionado básico de un servidor GNU/Linux o Windows.

**Evidencia evaluable:**

Lista de comprobación antes y después del bastionado, con justificación de los cambios.

---

## Sesión 5 — 26 de octubre

**Unidad 2. Monitorización y respuesta ante incidentes — RA2**

- Captura y análisis básico de tráfico.
- Registros de sistemas y servicios.
- Sistemas IDS e IPS.
- Detección basada en firmas y anomalías.
- Seguridad de redes inalámbricas.
- Fases de respuesta ante incidentes.
- Planes de contingencia y manuales de seguridad.

**Actividad práctica:**

Análisis de registros y tráfico para detectar un intento de acceso no autorizado.

**Evidencia evaluable:**

Informe de incidente con detección, contención, recuperación y medidas preventivas.

# Segundo bloque: protección perimetral

## Sesión 6 — 9 de noviembre

**Unidad 3. Diseño de la seguridad perimetral — RA3**

- Perímetro de red y zonas de confianza.
- Router frontera, pasarela y cortafuegos.
- Segmentación de redes.
- Zona desmilitarizada.
- Arquitecturas de subred protegida.
- Defensa perimetral, defensa interna y factor humano.

**Actividad práctica:**

Diseño de la red segura de una organización con LAN, DMZ, red de administración y acceso a Internet.

**Evidencia evaluable:**

Diagrama de red con zonas, servicios, flujos autorizados y controles de seguridad.

---

## Sesión 7 — 16 de noviembre

**Unidad 3. Acceso remoto seguro — RA3**

- Protocolos SSH, TLS e IPsec.
- VPN de acceso remoto y entre sedes.
- Túneles y cifrado.
- Pasarelas de acceso remoto.
- Autenticación mediante contraseñas, certificados y segundo factor.
- Sistemas centralizados de autenticación y conceptos AAA.
- Servidores RADIUS o equivalentes.

**Actividad práctica:**

Configuración de una conexión VPN o de una pasarela SSH con autenticación segura.

**Evidencia evaluable:**

Configuración, pruebas de conexión y breve documentación del acceso remoto.

---

## Sesión 8 — 23 de noviembre

**Unidad 4. Implantación de cortafuegos — RA4**

- Funciones y tipos de cortafuegos.
- Filtrado de paquetes e inspección con estado.
- Cortafuegos de equipo y de red.
- Política predeterminada.
- Reglas de entrada, salida y reenvío.
- Orden y prioridad de las reglas.
- Registro de conexiones y bloqueos.
- Pruebas y diagnóstico de conectividad.

**Actividad práctica:**

Configuración de un cortafuegos que permita únicamente los servicios autorizados.

**Evidencia evaluable:**

Conjunto de reglas, matriz de comunicaciones y pruebas que demuestren su funcionamiento.

---

## Sesión 9 — 30 de noviembre

**Unidad 5. Servidores proxy — RA5**

- Funciones de un servidor proxy.
- Proxy directo, transparente, anónimo y encadenado.
- Instalación y configuración básica.
- Configuración manual y automática de clientes.
- Almacenamiento en caché.
- Control de acceso y filtrado de contenidos.
- Métodos de autenticación.

**Actividad práctica:**

Instalación y configuración de un proxy con restricciones por red, usuario o dominio.

**Evidencia evaluable:**

Archivo de configuración y pruebas de accesos permitidos y denegados.

---

## Sesión 10 — 14 de diciembre

**Unidad 5. Proxy inverso y publicación segura — RA5**

- Funciones del proxy inverso.
- Publicación de servicios internos.
- Terminación TLS.
- Ocultación y protección de servidores.
- Balanceo básico de carga.
- Registros y monitorización.
- Pruebas de funcionamiento.
- Diagnóstico de problemas.

**Actividad práctica:**

Configuración de un proxy inverso para publicar de manera segura una aplicación web interna.

**Evidencia evaluable:**

Configuración, certificado utilizado, registros de acceso y documentación de la solución.

# Tercer bloque: alta disponibilidad y cumplimiento

## Sesión 11 — 21 de diciembre

**Unidad 6. Fundamentos de alta disponibilidad — RA6**

- Disponibilidad, fiabilidad y tolerancia a fallos.
- Continuidad del servicio.
- Acuerdos de nivel de servicio.
- RTO y RPO.
- Puntos únicos de fallo.
- Redundancia de servidores, red, alimentación y almacenamiento.
- RAID, replicación y copias de seguridad.

**Actividad práctica:**

Análisis de una infraestructura y detección de sus puntos únicos de fallo.

**Evidencia evaluable:**

Propuesta de mejora con redundancia, RTO, RPO y procedimiento de recuperación.

---

## Sesión 12 — 11 de enero

**Unidad 6. Clústeres, virtualización y balanceo — RA6**

- Servidores redundantes.
- Clústeres activo-pasivo y activo-activo.
- Latidos, quórum y aislamiento de nodos.
- Balanceadores de carga.
- Comprobaciones de salud.
- Persistencia de sesiones.
- Virtualización y alta disponibilidad.
- Introducción a contenedores y servicios replicados.

**Actividad práctica:**

Diseño e implantación inicial de un servicio web redundante con balanceo de carga.

**Evidencia evaluable:**

Diagrama de arquitectura y configuración inicial de los nodos y del balanceador.

---

## Sesión 13 — 18 de enero

**Unidad 6. Pruebas y documentación de alta disponibilidad — RA6**

- Conmutación por error y recuperación.
- Pruebas de caída de nodos.
- Monitorización de servicios.
- Pruebas de carga y estrés.
- Análisis de capacidad y tendencias.
- Continuidad de negocio y recuperación ante desastres.
- Documentación técnica de la solución.

**Actividad práctica:**

Provocar de manera controlada la caída de un nodo y comprobar la continuidad del servicio.

**Evidencia evaluable:**

Informe de prueba con tiempos de detección, conmutación, recuperación y conclusiones.

---

## Sesión 14 — 25 de enero

**Unidad 7. Legislación, normas y evaluación integradora — RA7**

### Primera parte: legislación y cumplimiento

- Reglamento General de Protección de Datos.
- Ley Orgánica de Protección de Datos y Garantía de los Derechos Digitales.
- Servicios de la sociedad de la información y comercio electrónico.
- Esquema Nacional de Seguridad.
- Marco NIS/NIS2.
- ISO/IEC 27001 e ISO/IEC 27002.
- Organismos de gestión de incidentes: INCIBE-CERT, CCN-CERT y CSIRT.
- Límites legales de las auditorías y pruebas de seguridad.

### Segunda parte: evaluación final

- Resolución de un caso integrado.
- Revisión de las evidencias prácticas.
- Defensa breve de la solución propuesta.
- Autoevaluación y conclusiones del módulo.

**Actividad práctica:**

Elaboración de una matriz de cumplimiento para la infraestructura trabajada durante el curso.

**Evidencia evaluable:**

Matriz normativa y memoria técnica final.

# Metodología recomendada para cada sesión

Cada sesión de tres horas puede organizarse de la siguiente manera:

- **45 minutos:** explicación y demostración.
- **105 minutos:** práctica guiada o reto técnico.
- **20 minutos:** documentación de resultados.
- **10 minutos:** puesta en común y cierre.

# Producto final del alumnado

Cada estudiante o equipo entregará un pequeño proyecto de infraestructura segura que reúna:

- Análisis de riesgos.
- Bastionado de sistemas.
- Diseño de red perimetral.
- Acceso remoto seguro.
- Reglas de cortafuegos.
- Servidor proxy o proxy inverso.
- Servicio de alta disponibilidad.
- Pruebas de caída y recuperación.
- Plan básico de contingencia.
- Revisión de cumplimiento normativo.

# Resumen horario

| Bloque | Resultados de aprendizaje | Horas |
|---|---|---:|
| Fundamentos y seguridad activa | RA1–RA2 | 15 |
| Seguridad perimetral, cortafuegos y proxy | RA3–RA5 | 15 |
| Alta disponibilidad | RA6 | 9 |
| Legislación y evaluación integradora | RA7 | 3 |
| **Total** | **RA1–RA7** | **42** |
