---
status: framed
segment: Team Leads y mandos medios que convocan sesiones de trabajo de más de 5 personas en cuentas Business Premium del sector tecnología (100 o más licencias, 3 o más países, facturación > USD 100M; 12.400 cuentas, 2,1 M de licencias), con equipos distribuidos en modalidad remota o híbrida
personas: [valentina-rios-ocampo, ricardo-lozano-garza, alvaro-pena-rojas]
---

# Opportunity: El trabajo en conjunto de la reunión se va fuera de Teams

Cuando un equipo distribuido de una tech multinacional necesita producir algo juntos durante una reunión (editar, priorizar, decidir), se va a Miro, Mural o FigJam. La reunión se parte en dos, la actividad en Teams cae y alguien tiene que pasar lo decidido a un documento después. Por qué ahora: el upgrade a Max en el segmento está en 3,1%, Ventas escucha "colaboración" en las conversaciones sobre Max y hay una ventana comprometida en CollabCon.

## Segment and personas

- **Quién vive el problema:** Team Leads y mandos medios que convocan y conducen las sesiones; los participantes lo sufren de forma secundaria.
- **Quién paga:** IT o compras de la cuenta Premium, que decide el upgrade a Max.
- **Personas existentes:** ninguna pertenece al segmento (las 4 son de salud privada chilena, mayormente presencial).
  - `constanza-vidal-munoz` y `francisca-bravo-herrera` sirven solo de contraste (convocante y compradora de otro sector).
  - `roberto-aguilera-silva` no aplica.
  - `alvaro-pena-rojas` sigue como persona negativa.
- **Personas del segmento (generadas 2026-09-16):**
  1. `valentina-rios-ocampo` — Team Lead de producto de un squad distribuido que facilita sesiones en Miro/FigJam (quien vive el problema).
  2. `ricardo-lozano-garza` — Gerente regional de Compras de Tecnología/SAM de una cuenta Premium multinacional que evalúa Max (quien paga; escéptico de cobrarlo como premium).

## Signals

| Signal | Provenance | Source |
|---|---|---|
| "Colaboración durante reuniones" es la 3ª categoría del portal de feedback en 12 meses: 4.700 solicitudes del segmento (editar un documento entre varios, votar o priorizar en vivo, no salir de Teams) | unverified | Brief de oportunidad, secc. 2 (portal de feedback, sin export) |
| 22% de los comentarios negativos post-reunión del segmento menciona la colaboración en vivo ("para hacer algo juntos terminamos en otra herramienta", "la pizarra es difícil de encontrar y nadie la usa", "pierdo tiempo pasando lo que decidimos a un documento después") | unverified | Brief de oportunidad, secc. 2 (encuesta post-reunión, sin n) |
| En 38% de las reuniones del segmento con más de 5 personas se comparte un enlace a Miro, Mural o FigJam; mientras dura, la actividad en Teams cae | unverified | Brief de oportunidad, secc. 2 (telemetría) |
| Whiteboard se abre en 6% de las reuniones del segmento; en la mitad de esos casos se cierra antes de 2 minutos | unverified | Brief de oportunidad, secc. 2 |
| "Colaboración" aparece en conversaciones de renovación sobre Max en cuentas grandes; sin registro de frecuencia | unverified | Brief de oportunidad, secc. 2 (Ventas) |
| Upgrade Premium → Max en el segmento: 3,1% de las cuentas en 12 meses | unverified | Brief de oportunidad, secc. 1 |
| Producto general: 29% de enlaces externos en reuniones de más de 5 personas; notas 8%; 37% de las organizaciones con Slack o Google Chat; "el equipo ya usa otras herramientas" como motivo de baja | unverified | product/overview.md (brief de clase, secc. 3–4) |
| Convocante que no documenta en vivo y después nadie recuerda lo decidido (fuera del segmento) | synthetic | product/personas/constanza-vidal-munoz.md |

## Business outcome

Commercial.

- **Principal:** tasa de upgrade a Max en el segmento (mueve el ingreso por licencia).
- **Protegido:** retención en la renovación.
- **Referencia derivada:** USD 8/usuario/mes × 2,1 M de licencias ≈ USD 2 M anuales por cada punto porcentual de licencias que sube de plan. Recuperar el presupuesto de USD 5 M en un año exige unos +2,5 pp.

## Constraints

- Presupuesto máximo: USD 5 M.
- Presentación en CollabCon, en unos 5 meses (≈ febrero 2027). Es un compromiso de fecha, no evidencia.
- Cualquier solución debe cumplir: facilidad de uso, accesibilidad, compatibilidad con Microsoft 365, privacidad y seguridad corporativas, tiempo real y bajo impacto en el rendimiento de la reunión.

## Beliefs

Referencias a product/overview.md (registro único):

- [opportunity: colaboracion-en-vivo-fuera-de-teams] [value] En las sesiones de más de 5 personas del segmento donde se comparte un enlace a Miro, Mural o FigJam, los participantes co-editan o priorizan (no solo miran), y quien convoca dedica 15 minutos o más después a pasar lo decidido a otro documento.
- [opportunity: colaboracion-en-vivo-fuera-de-teams] [viability] Resolver la colaboración en vivo dentro de Teams sube el upgrade del segmento a Max en +2,5 pp de licencias en 12 meses, porque los Team Leads lo piden o IT percibe menos fricción. Se refuta si el comprador lo considera algo que debería venir en Premium.
- [opportunity: colaboracion-en-vivo-fuera-de-teams] [viability] Las cuentas del segmento pagan hoy licencias de Miro, Mural o FigJam en un monto que hace que el upgrade a Max tenga costo neto defendible ante Finanzas si las reemplaza.
- Relacionadas, ya registradas: [product] [value] "Teams no es percibido como el lugar central de colaboración…"; [product] [viability] "El salto de precio a Business Max se justifica por funciones avanzadas de reuniones, pero las funciones menos usadas son justamente esas…"

## Research agenda

| Belief | Instrument | Decision it unlocks | By when |
|---|---|---|---|
| [value] co-edición + costo de transcribir | 1) **Datos propios:** en reuniones con enlace externo, cuántos participantes lo abren y cuánto dura la caída de actividad; codificar las 4.700 solicitudes y los comentarios del 22% por tarea. 2) `/design-survey` a Team Leads del segmento: frecuencia, tipo de uso, minutos post-reunión. 3) `/design-interview` a opt-ins | Perseguir la oportunidad (→ `/clarify-idea`) o descartarla / re-enmarcarla | 2026-10-16 |
| [viability] valor percibido | 1) **Datos propios:** empezar a registrar en CRM las menciones de "colaboración" en renovaciones de Max. 2) `/research-market`: cómo empaquetan y cobran la colaboración en vivo Zoom Workplace, Google Workspace, Miro y FigJam (¿incluida o premium?). 3) Entrevistas a IT o compras | Si la oportunidad es palanca de upgrade o solo de retención | 2026-10-30 |
| [viability] consolidación | 1) **Datos propios:** instalaciones y uso de las apps de Miro, Mural y FigJam en el admin center de las cuentas del segmento. 2) `/research-market`: precios enterprise y penetración en tech. 3) Pregunta de gasto en la encuesta a IT | Si el argumento de venta de Max es ahorro neto o valor percibido | 2026-10-30 |

Pendiente transversal: qué significa exactamente "colaboración en vivo" en el 22% de comentarios. Se resuelve con la codificación del primer paso.

## Candidate ideas (not evaluated)

- Herramientas colaborativas integradas en la reunión (el pedido original)
- Edición simultánea de documentos durante la llamada
- Votación o priorización en vivo
- Sesión de trabajo sin salir de Teams (tableros embebidos)
- Whiteboard más fácil de encontrar
- Traspaso automático de lo decidido a un documento
