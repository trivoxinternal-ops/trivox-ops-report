# AUDITORÍA TRIVOX — Sesión de Consultoría Interna
**Fecha:** 2026-06-19 · **Auditor:** Claude (Opus) · **Para:** Daniel + socios
**Objetivo:** identificar las oportunidades más fuertes de la empresa y disparar acción inmediata. Insumo para el Business Plan.

---

## 0. TL;DR (léelo aunque no leas nada más)

TRIVOX no tiene un problema de capacidad — tiene un problema de **empaque y distribución**.
Ya construimos 50+ productos reales. Cerramos casi todo lo que tocamos. Pero:

1. **Esos 50 productos están enterrados en carpetas, no en una vitrina que venda.** → Lo arreglé hoy: 40+ demos en un solo Demo Hub.
2. **Cada entrega se hace desde cero.** Cero productización. → La palanca #1 de margen.
3. **Casi cero leads.** Cerramos alto pero entra poco. → El cuello de botella real del negocio.
4. **Daniel es el único cuello en delivery, quoting, venta y marketing.** → Sin delegación, no hay escala.

**La tesis de escala:** convertir lo ya construido en **productos repetibles** + un **motor de leads de contenido** que usa el Demo Hub como prueba + una **flota de agentes/skills** que hace que un contractor (José/Brian/Dida) entregue sin que Daniel toque el teclado.

---

## 1. Diagnóstico honesto por área

| Área | Estado | Nota |
|------|--------|------|
| **Producto / capacidad técnica** | 🟢 Fuerte | 50+ proyectos construidos. Stack probado: Next, n8n, Netlify, agentes, scrapers, bots WA/IG, CRMs, generadores. |
| **Activos de venta (demos)** | 🟡 → 🟢 | Estaban dispersos. Hoy unificados en Demo Hub (40+). Ahora es el activo de marketing #1. |
| **Pipeline / leads** | 🔴 Crítico | Casi cero entrada. Dependemos de referidos y suerte. Sin esto, nada escala. |
| **Cierre / ventas** | 🟢 Alto | Tasa de cierre alta. El problema no es cerrar, es que entren. |
| **Delivery / operación** | 🔴 Cuello | Todo pasa por Daniel. Burnout. No documentado como producto repetible. |
| **Quoting / pricing** | 🟡 Riesgo | Instinto de Daniel sobreprecia (memoria confirmada). Falta Quote-QA antes de enviar. |
| **Delegación** | 🟡 En proceso | José (comisión), Brian (dev), Dida (PM/delivery). Modelo correcto: acceso scopeado a herramientas off-shelf, NO plataforma propia. |
| **Marca / sitio** | 🟡 | Branding sólido (kit existe). Sitio no convierte ni rankea — no esperar por él. |
| **Margen / caja** | 🔴 | Proyectos one-off, sin recurrencia ni retainers sistemáticos. |

---

## 2. El activo escondido: inventario de lo ya construido

Esto es oro. Cada uno = demo + case study + producto potencial. (Fuente: `Claude Code/` + `trivox-demo-hub/`.)

**Ventas & Atención al cliente**
- Bot de ventas WhatsApp (Fire School / obf-wa-bot) · Bot FB Messenger · AI Closer · Voice receptionist · Lead qualifier · Instagram DM agent

**Automotriz (vertical más desarrollado)**
- CarDeals Marketplace (prod) · Dealership lead scraper · Auto CRM · Alpha Auto Sales site · Wilson Moto Marketplace · CarDeals video engine

**Marketing & Contenido**
- SEO Agent · Marketing Audit Tool · ROI Calculator · Ads OS (command center) · Content engine · Review responder

**Operación interna**
- Invoice generator · Quote generator · Client onboarding · Paystub generator · TRIVOX CRM · Approval OS (Yuki) · Report engine

**IA a la medida / verticales**
- English Tutor (Profe Marco, $199/mo) · Real estate agent · Life insurance agent · Cognizance (clínica psicología) · Faith & Finance (curso) · jfoto (fotógrafo) · iactas (legal)

**Construcción (nicho con 12 demos pulidos)**
- Takeoff calc · Estimate gen · Change order · Bid analyzer · Daily site report · Employee cost calc · Accounting hub · Command center · Growth system · Voice agent · Campos demo · Report engine

→ **~45 productos reales.** No necesitamos inventar nada para tener 40 demos. Solo empaquetar.

---

## 3. Mapa de oportunidades (rankeadas por impacto × facilidad)

### 🥇 OPORTUNIDAD 1 — Productizar 3 "ofertas estrella" (margen + escala)
De los 45, elegir **3 productos repetibles** con precio fijo, alcance fijo y entrega por checklist:
1. **AI Sales Agent (WhatsApp/IG + booking)** — el más universal, todo negocio lo quiere. Setup $X + retainer mensual.
2. **Marketing Audit → Fix retainer** — el Audit Tool es el gancho (lead magnet), el fix es el retainer.
3. **Vertical Site + AI Agent** (clínica/inmobiliaria/fotógrafo/auto) — plantilla reusable, cambia el nicho.
→ **Por qué:** matar el "todo desde cero". Margen sube, delegable a Brian/Dida con checklist. **Acción:** ver `BUSINESS-PLAN-TRIVOX.md` §Ofertas.

### 🥈 OPORTUNIDAD 2 — Motor de leads de contenido (el cuello real)
Ahora SÍ tenemos material: 40+ demos = 40+ videos case-study.
- José en cámara + Jorge/editor. LinkedIn primero (B2B Toronto), 3x/semana, batch filming.
- Demo Hub como lead magnet en cada post ("mirá la demo en vivo").
- Outbound blitz: 25 tibios + 25 fríos, usando demos como prueba.
→ **Por qué:** sin entrada, lo demás es teoría. **Skill nueva:** `case-study-video-script` (abajo).

### 🥉 OPORTUNIDAD 3 — Flota de agentes/skills que hace a Daniel innecesario en delivery
Cada paso manual de Daniel → un skill o agente. (Ver §4 y §5.)
→ **Por qué:** desbloquea escala + arregla burnout. Daniel se queda en: traer, cerrar, quotear, delegar.

### OPORTUNIDAD 4 — Retainers / recurrencia
Todo lo que entregamos puede tener una capa de "mantenimiento + optimización mensual". Pasar de proyecto a MRR.

### OPORTUNIDAD 5 — Demo Hub como producto de venta self-serve
El Hub no es solo interno: es la mejor herramienta de venta. Mandarlo en frío, embeberlo en propuestas, usarlo en llamadas.

### OPORTUNIDAD 6 — Paquetizar por vertical
Tenemos demos en auto, construcción, salud, legal, inmobiliaria, educación. Cada vertical = una landing + un pitch + un set de demos filtrado.

---

## 4. SKILLS NUEVAS a construir (conectar a la flota)

Cada skill = un proceso de Daniel convertido en algo repetible y delegable. **Las marcadas ✅ las dejé creadas hoy** en `.claude/skills/`.

| Skill | Qué hace | Estado |
|-------|----------|--------|
| ✅ `quote-qa` | Revisa una cotización antes de enviarla: margen, sanidad de precio, anti-sobreprecio (memoria de Daniel). | Creada |
| ✅ `trivox-demo-builder` | Genera una demo branded de un producto nuevo con el design system TRIVOX. | Creada |
| ✅ `case-study-video-script` | Convierte una demo en un guion de video de 30-60s para José (hook, problema, demo, CTA). | Creada |
| ✅ `outbound-blitz` | Genera mensajes de outbound en frío/tibio personalizados usando el Demo Hub como prueba. | Creada |
| ✅ `trivox-proposal` | Arma una propuesta branded (alcance, precio por tiers, ROI) desde un brief corto. | Creada |
| `client-intake-to-spec` | Convierte una llamada/brief de cliente en un spec de entrega con checklist. | Backlog |
| `delivery-checklist` | Para cada oferta estrella, el checklist exacto de entrega (delegable). | Backlog |
| `vertical-landing` | Genera una landing por vertical (auto/salud/legal...) con demos filtradas. | Backlog |

## 5. AGENTES NUEVOS a construir

| Agente | Rol | Estado |
|--------|-----|--------|
| ✅ `trivox-lead-finder` | Encuentra leads (negocios sin web/sin bot/con malas reviews) en nichos de Toronto y arma lista lista-para-contactar. | Definido hoy |
| ✅ `trivox-delivery-pm` | Orquesta una entrega: toma el spec, reparte tareas a sub-agentes, verifica contra checklist (rol Dida). | Definido hoy |
| ✅ `trivox-quote-builder` | Construye la cotización + corre `quote-qa` antes de devolverla. | Definido hoy |
| `trivox-content-engine` | Toma 1 idea → semana de contenido multiplataforma + guiones de video de los demos. | Backlog |
| `trivox-onboarding` | Corre el onboarding de un cliente nuevo punta a punta (contrato, depósito, kickoff). | Backlog |

---

## 6. Plan de acción 30 / 60 / 90

**Próximos 30 días (CAJA + DISTRIBUCIÓN)**
1. Lanzar Demo Hub portfolio (✅ hecho hoy) → mandarlo en outbound esta semana.
2. Grabar 3 videos case-study de los mejores demos (José + editor). Postear LinkedIn.
3. Outbound blitz: 25 tibios + 25 fríos con el skill `outbound-blitz`.
4. Definir las 3 ofertas estrella con precio fijo (ver Business Plan).
5. Quote-QA activo en TODA cotización (skill `quote-qa`).

**60 días (PRODUCTIZACIÓN + DELEGACIÓN)**
6. Checklist de entrega para las 3 ofertas → primera entrega delegada a Brian/Dida sin Daniel.
7. Motor de contenido en ritmo (3x/sem). Demo Hub como lead magnet fijo.
8. Primer retainer mensual cerrado (mantenimiento + optimización).

**90 días (ESCALA)**
9. Una landing por vertical con demos filtradas.
10. Flota de agentes operando delivery; Daniel solo trae/cierra/quotea/delega.
11. MRR objetivo: medir % de ingreso recurrente vs one-off.

---

## 7. Lo que NO hacemos (foco)
- ❌ Construir una plataforma propia para contractors → usar herramientas off-shelf con acceso scopeado (memoria confirmada).
- ❌ Esperar a que el sitio web traiga leads → contenido + outbound traen tráfico, el sitio convierte.
- ❌ Cotizar por instinto → siempre Quote-QA.
- ❌ Seguir entregando todo desde cero → productizar.

---

## 8. Acciones que TOMÉ HOY (mientras estabas fuera)
Ver `ACCION-LOG-2026-06-19.md` para el detalle. Resumen:
- ✅ 40+ demos unificados en `trivox-demo-hub/portfolio.html` (30 nuevos + 12 existentes).
- ✅ 5 skills nuevas creadas y listas en `.claude/skills/`.
- ✅ 3 agentes nuevos definidos en `.claude/agents/`.
- ✅ Este documento de auditoría + el Business Plan spine.
