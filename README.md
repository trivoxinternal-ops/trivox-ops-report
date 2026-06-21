# TRIVOX — Ops & Weekly Report Repo (PRIVATE)

Repo privado con los documentos de estrategia + el Demo Hub de TRIVOX. Lo usa el **agente semanal de reportes** (rutina programada, corre cada lunes 8am Toronto).

⚠️ **NO subir aquí:** contratos, NDAs, PDFs legales, datos/PII de clientes, claves, `.env`. Solo estrategia + material de marketing.

## Contenido
- `AUDITORIA-TRIVOX-2026.md` — auditoría de oportunidades.
- `BUSINESS-PLAN-TRIVOX.md` — business plan (3 ofertas estrella, pricing, motor de adquisición).
- `ACCION-LOG-2026-06-19.md` — log de la sesión autónoma inicial.
- `TRIVOX-SCALE-PLAN.md`, `MARKETING-CONTENT-ENGINE.md`, `alcance-servicios-automatizacion.md` — estrategia.
- `trivox-demo-hub/` — 42 demos + `portfolio.html` (activo de venta #1).
- `REPORTS/` — donde el agente guarda `WEEKLY-REPORT-<fecha>.md` cada semana.

## Instrucciones del agente semanal (chief-of-staff / Jarvis)
Cada lunes 8am (America/Toronto):
1. `git pull`. Revisa el log de git de los últimos 7 días + los docs de estrategia para entender qué cambió.
2. Escribe `REPORTS/WEEKLY-REPORT-<YYYY-MM-DD>.md`, en español, conciso, tono chief-of-staff, cubriendo:
   - **Qué se entregó / cambió esta semana** (commits, demos nuevos, cambios en portfolio).
   - **Progreso de las 3 ofertas estrella** (A: AI Sales Agent · B: Audit→Fix · C: Vertical Site+Agent).
   - **Leads / outbound** (estado, si hay data).
   - **Skills / agentes nuevos** añadidos en `.claude/`.
   - **Top 3-5 prioridades de la semana entrante**, atadas al plan 30/60/90 de la auditoría.
3. Commit + push del reporte.
4. Crea un **borrador en Gmail** a danielfelipeortizreyes@gmail.com, asunto `TRIVOX — Reporte semanal <fecha>`, con el reporte. Si el borrador falla, igual deja el archivo commiteado.
