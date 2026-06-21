# Pre-Meeting Prep — Daniel (Automation Engineer, primer hire técnico)

> Constructora · rol: dueño de la infra operativa. 3 pilares que dijeron textual:
> **AI estimating pipelines → accounting integrations → real-time dashboards.**
> Remoto, async, acceso directo a founders, **path contractor → equity partner.**
> Stack que nombraron: **n8n / Make.com / OpenAI API.**

---

## 1. El frame mental (lo más importante)

No vas como "el que hace tareas". Vas como **el dueño de la infraestructura técnica** — el primer hire que ARQUITECTA el sistema sobre el que corre el negocio. Hablá con mentalidad de owner: arquitectura, confiabilidad, escalabilidad, no solo "yo conecto esto con aquello".

Tu superpoder: **ya construiste exactamente esto** (estimating, invoicing, dashboards) para clientes reales con TRIVOX. No estás aprendiendo en su tiempo — llegás con producto. Los demos lo prueban.

---

## 2. Hablá fluido sus 3 pilares

**AI estimating pipelines**
- Cómo lo armarías: data histórica de proyectos + scope → LLM estructurado + templates → estimate con line items por división → **human-in-the-loop** para revisar antes de mandar.
- Menciona: edge cases, validación, por qué un estimate no se manda 100% automático (riesgo).

**Accounting integrations**
- Nombres que debes soltar: **QuickBooks Online API, Xero**, y construcción-específico: **Procore, Buildertrend**.
- Conceptos: AR/AP, progress billing, reconciliación, holdback/retainage, facturación por milestone.

**Real-time dashboards**
- Flujo: fuentes (forms, n8n, DB/Airtable) → capa de datos → dashboard live.
- KPIs que le importan a un GC: budget burn, schedule variance, RFIs abiertos, change orders, cash flow, WIP.

**Decisiones de arquitectura (van a tantear esto):**
- Cuándo **n8n vs Make** vs código custom. Dónde entra **OpenAI/Claude**. Manejo de errores/reintentos. Control de costos de API. Privacidad de datos.

---

## 3. Habla su idioma (jerga de construcción = credibilidad instantánea)

GC (general contractor) · sub (subcontratista) · RFI · change order · takeoff · draw schedule · holdback/retainage · progress billing · facturación tipo AIA (G702/G703) · bid · markup · WIP report · COGS.

> Soltar 4-5 de estos en contexto = "este man sí entiende mi mundo".

---

## 4. Preguntas que VOS hacés (jugada de first hire)

- ¿Cuál es el cuello de botella #1 hoy en operaciones?
- ¿Cómo hacen el estimating ahora — manual, Excel?
- ¿Qué stack/herramientas usan hoy? ¿Qué sistema de accounting?
- Tamaño del equipo, cuántos proyectos a la vez.
- ¿Qué significa "owning the infrastructure" para ustedes en los primeros 90 días?
- El path contractor → equity: ¿cómo se ve concreto? (timeline, milestones, % aprox).

---

## 5. Plata / equity (no negociar hoy, sí entender)

- Hoy: **entender el path**, no cerrar números. Mostrá mentalidad de largo plazo/owner.
- Pedí claridad: ¿cuánto tiempo de contractor antes del equity? ¿qué milestones? ¿vesting?
- No te sobre-comprometas a equity sin entender términos.

---

## 6. ⚠️ El tema TRIVOX (preparalo, no te agarren en frío)

Vos corrés TRIVOX (agencia de automatización con IA) y vas a ser su engineer in-house. Posible tensión: tiempo, IP, conflicto.
- Posición sugerida: TRIVOX = **prueba de que sabés construir esto**, no un competidor (TRIVOX sirve SMBs/servicios, no construction-tech).
- Decidí antes de entrar **cómo presentás TRIVOX**: ¿lo mencionás como portafolio/experiencia? Probablemente sí — es tu mejor credencial. Pero ten clara la respuesta si preguntan "¿y eso compite o te quita tiempo?".

---

## 7. Logística (no falles en lo bobo)

- Laptop **cargada** + cargador.
- **Demos cargados OFFLINE** — abrí `trivox-demo-hub/index.html` antes de salir, no dependás del wifi del lugar. (Solo la card de Cognizance necesita internet.)
- Backup en el celular por si acaso.
- Llegá temprano. Full screen. Navegá el hub con calma.

---

## 8. Regla de oro de los demos

**Mostrá el resultado y la velocidad. Nunca el código, n8n ni los prompts.**
Input → "la IA piensa" → output bonito. Si preguntan "¿cómo funciona?": "Es un pipeline custom que combina varios modelos y automatizaciones — el punto es el resultado: lo que tomaba horas, ahora segundos."
