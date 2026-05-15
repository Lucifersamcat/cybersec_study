# Tareas y Asignaciones Resueltas

---

## MÓDULO 1 — Taller: Identificación de Amenazas y Vulnerabilidades

### Escenario 1: Wi-Fi pública sin contraseña

**Vulnerabilidad:** La red Wi-Fi no tiene cifrado ni autenticación, lo que permite que cualquier persona en el mismo entorno se conecte y observe el tráfico de datos que circula por ella.

**Amenaza:** Ataque de tipo **Man-in-the-Middle (MitM)**. El atacante se posiciona entre Juan y el punto de acceso, interceptando correos, contraseñas y cualquier información que Juan transmita sin cifrar.

---

### Escenario 2: Contraseña débil en redes sociales

**Vulnerabilidades:**
- Contraseña extremadamente débil ("12345") — fácilmente adivinable por fuerza bruta.
- Reutilización de la misma contraseña en múltiples cuentas — si una cae, todas caen.

**Amenaza:** Ataque de **fuerza bruta** o **credential stuffing** (uso de contraseñas filtradas en otras plataformas).

**Medidas de protección:**
- Usar contraseñas largas y únicas para cada cuenta (mínimo 12 caracteres, combinando letras, números y símbolos).
- Activar la **autenticación de dos factores (2FA)** en todas las cuentas.
- Usar un gestor de contraseñas para no tener que memorizarlas todas.

---

### Escenario 3: Phishing por correo electrónico

**Vulnerabilidad:** Roberto no verifica la autenticidad del correo antes de actuar. La falta de conocimiento sobre señales de phishing lo hace susceptible al engaño.

**Amenaza:** **Phishing** — suplantación de identidad de una entidad de confianza (el banco) para robar credenciales e información financiera.

**¿Cómo puede Roberto saber si el correo es legítimo?**
- Revisar el dominio del remitente (un banco real no usa Gmail u otros dominios genéricos).
- No hacer clic en enlaces del correo; ingresar directamente escribiendo la URL del banco en el navegador.
- Los bancos legítimos **nunca** piden credenciales por correo.
- Verificar si hay errores ortográficos, diseño genérico o urgencia exagerada en el mensaje.
- Llamar directamente al banco para confirmar si enviaron el correo.

---

## MÓDULO 1 — Glosario de Ciberseguridad

| Término | Definición |
|---|---|
| **Malware** | Software malicioso diseñado para dañar, infiltrarse o robar información de un sistema sin autorización. |
| **Ransomware** | Tipo de malware que cifra los archivos de la víctima y exige un pago (rescate) para devolver el acceso. |
| **Firewall** | Sistema de seguridad que monitorea y controla el tráfico de red según reglas predefinidas. |
| **Autenticación de dos factores (2FA)** | Método de seguridad que requiere dos formas de verificación para acceder a una cuenta. |
| **Ingeniería social** | Técnicas de manipulación psicológica para engañar a personas y obtener información confidencial. |
| **Phishing** | Intento de obtener información sensible haciéndose pasar por una entidad confiable. |
| **Vishing** | Phishing realizado mediante llamadas telefónicas. |
| **SMShing** | Phishing mediante mensajes de texto (SMS). |
| **Hacking ético** | Práctica de atacar sistemas con permiso del propietario para detectar vulnerabilidades antes que actores maliciosos. |
| **Pentesting** | Prueba de penetración; simulación de ataque para evaluar la seguridad de un sistema. |
| **VPN** | Red privada virtual que cifra la conexión a internet y protege la privacidad del usuario. |
| **Cifrado** | Proceso de convertir información en un formato ilegible para protegerla de accesos no autorizados. |
| **Backdoor** | Acceso oculto a un sistema, instalado por un atacante para regresar sin ser detectado. |
| **Zero-day** | Vulnerabilidad desconocida para el fabricante del software, explotada antes de que exista un parche. |
| **Media dropping** | Técnica de ataque que consiste en dejar dispositivos (USB, CD) en lugares públicos para que alguien los conecte. |

---

## MÓDULO 2 — Práctica 1: Análisis de Caso

**Caso:** Un estudiante logra acceder al correo institucional de un profesor sin autorización. Desde allí, descarga exámenes, modifica información y comparte los archivos con otros compañeros.

---

### 1. Explicación del caso

Un estudiante aprovechó alguna vulnerabilidad (contraseña débil, sesión abierta o acceso no autorizado) para entrar al correo institucional de su profesor sin ningún permiso. Una vez dentro, no solo revisó el contenido sino que descargó material confidencial como exámenes futuros, alteró información del sistema y distribuyó ese material entre otros compañeros. Esta acción va más allá de una simple travesura académica: implica violación de privacidad, manipulación de datos institucionales y distribución no autorizada de información confidencial. El daño afecta tanto al profesor como a la institución, comprometiendo la integridad del proceso educativo y la confianza en los sistemas digitales.

### 2. Delitos cometidos

- **Acceso ilícito** a un sistema de información (Art. 6, Ley 53-07).
- **Daño y alteración de datos** — modificó información del correo (Art. 10).
- **Interceptación y uso de datos por acceso ilícito** (Art. 6, Párrafo I).
- **Uso de dispositivos o medios para acceder sin autorización** (Art. 7).

### 3. Por qué es ilegal

El estudiante accedió a un sistema informático que no le pertenecía y para el cual no tenía autorización. La Ley 53-07 protege la confidencialidad e integridad de los sistemas de información; ingresar sin permiso, modificar datos y distribuirlos constituye una violación directa a estos principios, independientemente de si la intención era "solo ver" los exámenes.

### 4. Qué establece la Ley 53-07

- **Art. 6:** El acceso ilícito a un sistema informático se sanciona con 3 meses a 1 año de prisión y multa.
- **Art. 6, Párrafo I:** Si del acceso resulta modificación o revelación de datos confidenciales, la pena sube a 1–3 años y multa mayor.
- **Art. 10:** La alteración de datos con fines fraudulentos se sanciona con 3 meses a 1 año (o hasta 3 años si es empleado o vinculado a la institución).

### 5. Consecuencias legales

- Prisión de 1 a 3 años por acceso ilícito con modificación de datos.
- Multa económica según lo establecido por la ley.
- Posible expulsión de la institución educativa.
- Antecedentes penales que afectarían su futuro académico y profesional.
- Los compañeros que recibieron y usaron el material podrían ser considerados cómplices.

### 6. Medidas de prevención

1. **Contraseñas seguras y únicas** para cuentas institucionales, con cambio periódico.
2. **Autenticación de dos factores (2FA)** en el correo institucional.
3. **Cerrar sesión** en dispositivos compartidos o públicos después de usarlos.
4. **Capacitar a estudiantes y docentes** sobre delitos informáticos y sus consecuencias legales.
5. **Monitoreo de accesos** por parte del departamento de TI de la institución.

### 7. Reflexión personal

Ante esa situación, lo correcto sería no intentar acceder a cuentas ajenas bajo ninguna circunstancia. Si accidentalmente se descubriera una vulnerabilidad en el sistema, lo ético es reportarla al departamento de tecnología de la institución, no explotarla. Respetar la seguridad digital es fundamental porque los sistemas informáticos son extensiones de nuestra privacidad y de nuestra identidad. Violarlos no solo afecta a una persona, sino que erosiona la confianza colectiva en las instituciones. En un mundo cada vez más digital, actuar con integridad en línea es tan importante como hacerlo en la vida presencial.

---

## MÓDULO 2 — Práctica 2: Caso Real — Hackeo a Uber (2022)

### 1. Descripción del caso

En septiembre de 2022, un joven hacker de 18 años logró infiltrarse en los sistemas internos de Uber, una de las empresas tecnológicas más grandes del mundo. El atacante utilizó **ingeniería social**: se hizo pasar por personal de TI de Uber y convenció a un empleado de que compartiera sus credenciales de acceso, alegando que necesitaba verificar su cuenta. Con esas credenciales, accedió a herramientas internas, sistemas de seguridad, bases de datos de empleados y hasta publicó mensajes en los canales internos de Slack de la empresa.

### 2. Tipo de delito tecnológico

- **Ingeniería social** combinada con **acceso ilícito** a sistemas informáticos.
- **Interceptación y uso de datos confidenciales** de empleados y sistemas.
- **Acceso no autorizado a infraestructura crítica** de la empresa.

### 3. Relación con la Ley 53-07

Bajo la Ley 53-07, este caso encuadra en:
- **Art. 6** — Acceso ilícito a sistemas de información.
- **Art. 6, Párrafo I** — Revelación de datos confidenciales obtenidos por acceso ilícito.
- **Art. 9** — Interceptación de datos pertenecientes a otra persona o entidad.

### 4. Consecuencias para el responsable

El joven fue arrestado en el Reino Unido. En 2023 fue declarado culpable de varios cargos de hackeo y fraude informático bajo la legislación británica, enfrentando potencialmente años de prisión. El caso destacó la importancia del factor humano como la mayor vulnerabilidad en ciberseguridad.

### 5. Impacto en la víctima

Uber sufrió exposición de datos internos sensibles, daño reputacional significativo, costos millonarios en respuesta al incidente y reforzamiento de seguridad. Los empleados cuyos datos quedaron expuestos enfrentaron riesgo de ser blanco de ataques de phishing y robo de identidad.

### 6. Medidas que hubieran evitado el caso

1. **Capacitación en ingeniería social** para todos los empleados, especialmente en verificación de identidad antes de compartir credenciales.
2. **Autenticación multifactor (MFA)** obligatoria en todos los sistemas internos.
3. **Política de privilegio mínimo**: que cada empleado solo acceda a los sistemas estrictamente necesarios para su rol.

### 7. Conclusión personal

El caso de Uber demuestra que la tecnología más avanzada puede ser neutralizada por un simple engaño humano. La ciberseguridad no es solo un asunto técnico; es también un asunto de cultura y educación. Aprender a verificar identidades, desconfiar de solicitudes urgentes e inesperadas y nunca compartir credenciales son hábitos que cualquier persona puede adoptar. En mi vida cotidiana, aplico esto no compartiendo contraseñas, activando 2FA en mis cuentas y siendo crítico ante mensajes que generen urgencia o pidan datos personales.

---

## MÓDULO 2 — Práctica 3: Caso Creado — Fraude con Deepfake de Voz

### 1. Descripción del caso

Sofía es contadora en una empresa mediana de Santo Domingo. Un lunes por la mañana recibe una llamada de quien parece ser su jefe directo, el director financiero Carlos Méndez. La voz es perfectamente reconocible. "Carlos" le indica con urgencia que necesita que realice una transferencia de RD$800,000 a una cuenta nueva de un proveedor, ya que hay un contrato urgente que cerrar antes del mediodía. Le pide discreción porque "la negociación es confidencial". Sofía, confiando en la voz de su jefe, realiza la transferencia. Horas después, el director real llama preguntando por otra cosa y Sofía se da cuenta de que nunca ordenó ninguna transferencia. Los fondos ya habían sido movidos a múltiples cuentas en el extranjero. Los atacantes habían usado una herramienta de **clonación de voz con inteligencia artificial (deepfake de voz)** alimentada con audios públicos del director extraídos de videos corporativos.

### 2. Delito tecnológico involucrado

- **Estafa electrónica** mediante engaño y suplantación de identidad (Art. 15, Ley 53-07).
- **Robo de identidad** usando tecnología de clonación de voz (Art. 17).
- **Obtención ilícita de fondos** mediante transferencia electrónica fraudulenta (Art. 14).
- **Chantaje o coacción digital** al crear urgencia y secretismo para presionar a la víctima (Art. 16).

### 3. Relación con la Ley 53-07

- **Art. 14** (Obtención ilícita de fondos): La transferencia fue obtenida mediante engaño tecnológico — sancionado con 3 a 10 años de prisión.
- **Art. 15** (Estafa): El fraude fue realizado a través de un medio telemático — 3 meses a 7 años de prisión.
- **Art. 17** (Robo de identidad): Se usó tecnología para suplantar la identidad del director — 3 meses a 7 años de prisión.

### 4. Consecuencias legales

El o los responsables podrían enfrentar hasta 10 años de prisión por obtención ilícita de fondos, más penas adicionales por robo de identidad y estafa. La empresa podría también demandar civiles por los daños económicos sufridos.

### 5. Plan de prevención (4 acciones concretas)

1. **Protocolo de verificación doble:** Toda transferencia superior a un monto establecido debe ser confirmada por un segundo canal (llamada al número oficial registrado o confirmación presencial), nunca solo por una llamada entrante.
2. **Capacitación sobre deepfakes y vishing:** Informar a los empleados financieros sobre la existencia de tecnología de clonación de voz y la importancia de no actuar solo bajo presión verbal.
3. **Palabra clave secreta:** Establecer una contraseña verbal entre directivos y el equipo financiero para validar solicitudes urgentes sensibles.
4. **Política de transferencias con múltiples aprobadores:** Ninguna transferencia de alto valor puede ser autorizada por una sola persona, requiriendo firma digital de al menos dos cargos.

### 6. Cómo educar a otros sobre este delito

Organizaría una charla en la empresa mostrando ejemplos reales de deepfakes de voz (muchos están disponibles públicamente) para que los empleados experimenten en primera persona lo convincente que puede sonar. Luego explicaría el protocolo interno de verificación. El impacto visual y auditivo de escuchar una voz clonada es mucho más efectivo que solo leer sobre el tema. También distribuiría una guía de bolsillo con los pasos a seguir ante cualquier solicitud financiera urgente por teléfono.

### 7. Reflexión final

Estos delitos son cada vez más comunes porque la tecnología avanza más rápido que la conciencia de las personas sobre sus riesgos. El acceso a herramientas de inteligencia artificial que antes solo tenían actores estatales o grandes hackers, hoy está disponible para cualquier persona con conexión a internet. Como ciudadano digital, mi papel es mantenerme informado, cuestionar lo que parece demasiado urgente o inusual, y nunca subestimar la creatividad de quienes buscan engañar. La ciberseguridad no es responsabilidad exclusiva del departamento de TI; es de todos.

---

## CASOS PRÁCTICOS — Preguntas Guía Resueltas

### Caso 1: Acceso Ilícito y Violación de Privacidad (Juan e Instagram de María)

- **¿Qué delitos se están cometiendo?** Acceso ilícito (Art. 6), daño de datos (Art. 10) e invasión de privacidad (Art. 19).
- **¿Es legal acceder si ya tienes la contraseña?** No. La contraseña fue guardada sin intención de cederla permanentemente. Usar credenciales ajenas sin autorización expresa es acceso ilícito según la Ley 53-07, sin importar cómo se obtuvo la contraseña.
- **¿Qué derechos fueron vulnerados?** Derecho a la privacidad, a la integridad de la información personal y a la dignidad.
- **Consecuencias para Juan:** 3 meses a 3 años de prisión y multa, agravado por la publicación de contenido íntimo.

---

### Caso 2: Phishing y Fraude Electrónico (Pedro y el banco falso)

- **¿Qué tipo de delito se cometió?** Phishing (estafa electrónica, Art. 15) y obtención ilícita de fondos (Art. 14).
- **¿Quién es responsable?** El atacante es el principal responsable. El banco puede tener responsabilidad secundaria si no implementó sistemas de alerta ante transferencias inusuales.
- **Errores de Pedro:** Hacer clic en un enlace de un correo no verificado, no revisar el dominio del remitente, ingresar datos financieros en una página sin verificar su autenticidad.
- **Medidas preventivas:** Nunca ingresar credenciales desde enlaces de correo; activar alertas bancarias; usar autenticación de dos factores.

---

### Caso 3: Difamación y Suplantación de Identidad (cuenta falsa del profesor)

- **¿Qué delitos están involucrados?** Robo de identidad (Art. 17), difamación (Art. 21) e injuria pública (Art. 22).
- **¿Cómo afecta profesionalmente a la víctima?** Daña su reputación ante estudiantes, padres e institución; puede costarle su empleo y credibilidad académica.
- **¿Es un delito grave?** Sí. La combinación de suplantación y difamación pública tiene penas que suman varios años de prisión bajo la Ley 53-07.
- **¿Cómo demostrar quién creó la cuenta?** Mediante la dirección IP de registro de la cuenta, historial de dispositivos y metadatos solicitados a la plataforma con una orden judicial.

---

### Caso 4: Acceso No Autorizado al Sistema Escolar (Carlos y las calificaciones)

- **¿Carlos es culpable aunque haya "descubierto una falla"?** Sí. Descubrir una vulnerabilidad no da derecho a explotarla. Debió reportarla, no usarla en su beneficio.
- **¿Es hacking ético o delito?** Es un delito. El hacking ético requiere permiso explícito de la organización; Carlos actuó sin autorización y con beneficio económico propio.
- **Artículos aplicables:** Art. 6 (acceso ilícito), Art. 10 (alteración de datos), Art. 11 (sabotaje).
- **Consecuencias:** Hasta 3 años de prisión, multa y posible expulsión. Los estudiantes que pagaron podrían ser procesados como cómplices.
- **Cómo debió actuar:** Reportar la vulnerabilidad al departamento de TI o a las autoridades de la institución.

---

### Caso 5: Difusión de Contenido sin Consentimiento (fotos de Ana)

- **¿Es solo "un problema personal" o un delito?** Es un delito tipificado bajo la Ley 53-07 (Art. 19 y Art. 21) y puede calificar bajo Art. 23 si el contenido tiene carácter sexual.
- **¿Qué derechos fueron vulnerados?** Derecho a la privacidad, a la dignidad, a la imagen y a la integridad emocional.
- **Consecuencias legales:** Prisión de 6 meses a 2 años por invasión de privacidad; hasta 1 año adicional por difamación; penas mayores si aplica el Art. 23.
- **Cómo prevenir:** No compartir contenido íntimo digital en ninguna circunstancia; en caso de hacerlo, conservar evidencia del destinatario original; denunciar de inmediato al DICAT si ocurre la difusión.
