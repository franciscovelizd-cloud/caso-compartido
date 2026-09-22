---
source: secondary
method: mixed
date: 2026-09-16
question: ¿Cómo empaqueta y cobra el mercado la colaboración en vivo durante reuniones (incluida o premium), cuánto cuestan Miro/Mural/FigJam para una cuenta enterprise, y qué dice eso sobre las creencias de la oportunidad?
opportunity: 2026-09-15-2148-colaboracion-en-vivo-fuera-de-teams
---

# Research: Colaboración en vivo fuera de Teams

**Método.** Búsqueda web el 2026-09-16, priorizando páginas de precios y documentación de los propios proveedores. Cuando el sitio oficial no se pudo leer (Zoom Workplace, Google Workspace), se usaron fuentes secundarias y quedan marcadas. Las etiquetas de procedencia usan `[verificado: URL — 2026-09-16]` o `[conocimiento del modelo — verificar]`. Los cálculos propios aparecen como `[cálculo derivado]` e indican de qué datos salen.

**Nota sobre el caso vs. el mundo real.** El brief es un caso de clase. En el catálogo real de Microsoft no existe un plan "Business Max". Los planes Business tienen un tope de 300 usuarios por tenant, y Business Premium cuesta USD 22 por usuario al mes [verificado: https://www.microsoft.com/en-us/microsoft-365/business/microsoft-365-business-premium — 2026-09-16] [verificado: https://learn.microsoft.com/en-us/microsoft-365/business-premium/microsoft-365-business-faqs — 2026-09-16]. Los análogos reales del salto de USD 8 son Teams Premium (USD 10) y Business Premium con Copilot (USD 32, es decir +USD 10). Este documento respeta las cifras del caso y usa los datos reales solo como referencia de mercado.

## Resumen: lo que cambia decisiones

1. **En el mercado, la colaboración en vivo viene incluida o es barata. No es el eje de los planes premium.** Microsoft ya incluye Whiteboard y Loop en todos sus planes Business. Google cerró Jamboard y delegó la pizarra a Miro, FigJam y Lucidspark. Zoom incluye una pizarra básica gratis, la versión ilimitada desde Business y cobra USD 2,07 por la versión avanzada. Los tiers premium reales (Teams Premium, Copilot) se cobran por **IA, seguridad y gestión**, no por colaboración. Esto tensiona directamente la creencia de que la colaboración justifica USD 8 más.
2. **El argumento de "reemplazar Miro/Mural/FigJam" es aritméticamente difícil.** Esos productos cobran por *miembro*, no por participante: los visitantes editan gratis. Para que el upgrade a Max (USD 8 × *todas* las licencias) se pague solo, al menos el 40% de las licencias de la cuenta tendría que tener asiento pagado de Miro Business a precio de lista. Con FigJam (asiento colaborador de USD 5) es imposible. Además, el 81% del gasto SaaS lo controlan las unidades de negocio, no IT, así que ese gasto puede ni siquiera ser visible para quien compra Max.
3. **Teams ya tiene casi todo lo que se propone como idea candidata.** Whiteboard dentro de la reunión, componentes Loop, apps de Miro y FigJam dentro de la reunión (con "Share to stage" y co-edición) y el agente Facilitator (notas colaborativas, agenda y tareas, que requiere Copilot). Por eso el problema del 6% de apertura de Whiteboard parece ser de **adopción, calidad y descubribilidad**, no de ausencia de funciones. Es un reencuadre relevante antes de `/clarify-idea`.

## Competidores directos: suites de reuniones

| Producto | ¿Colaboración en vivo en la reunión? | Cómo se empaqueta | Precio de referencia | Procedencia |
|---|---|---|---|---|
| **Microsoft 365 / Teams** (actual) | Whiteboard y anotaciones colaborativas; Loop | **Incluido** en Business Basic y Standard | Basic USD 7; Premium USD 22; Premium + Copilot USD 32 | [verificado: https://www.microsoft.com/en-us/microsoft-teams/compare-microsoft-teams-business-options — 2026-09-16] |
| **Teams Premium** (add-on) | Ninguna función de colaboración en vivo en la lista: recap inteligente, marca de agua, E2EE, plantillas, subtítulos traducidos, analítica | Add-on premium centrado en IA, protección y personalización | USD 10 por usuario al mes | [verificado: https://learn.microsoft.com/en-us/microsoftteams/enhanced-teams-experience — 2026-09-16]; precio [verificado: https://www.microsoft.com/en-us/microsoft-teams/compare-microsoft-teams-business-options — 2026-09-16] |
| **Facilitator en Teams** | Notas en tiempo real que todos co-editan, agenda con temporizador y tareas por @mención | Requiere licencia Copilot solo para quien lo activa; los demás participantes internos ven y editan | Copilot Business ≈ USD 21 (standalone, desde el 1-jul-2026) | [verificado: https://support.microsoft.com/en-us/teams/copilot/facilitator-in-microsoft-teams-meetings — 2026-09-16]; precio [verificado: https://www.cyberduo.com/blog/microsoft-365-changes-july-2026/ — 2026-09-16] (partner, precios de lista aproximados) |
| **Zoom Workplace** | Whiteboard nativo que se abre "con un clic" desde la reunión | **Escalonado:** Basic (3 pizarras) incluido en Free y Pro; Unlimited incluido en Business, Business Plus y Enterprise Essentials; Whiteboard Plus en Enterprise Plus o como add-on | Add-on Whiteboard Plus USD 2,07 por usuario al mes (anual); Pro USD 14,16; Business USD 15,58 el primer año, luego USD 18,33 | Pizarra [verificado: https://www.zoom.com/en/products/online-whiteboard/ — 2026-09-16]; planes [verificado: https://tech.co/web-conferencing/zoom-pricing-guide — 2026-09-16] (terceros, actualizado 2026-09-08; la página oficial no cargó) |
| **Google Workspace / Meet** | Sin pizarra propia desde 2024. Integra FigJam, Lucidspark y Miro; FigJam se co-edita dentro de Meet sin cuenta Figma | **Delegado a partners** | Precios de Workspace: desconocido (la página oficial no mostró cifras) | [verificado: https://workspaceupdates.googleblog.com/2023/09/the-next-phase-of-digital-whiteboarding-for-google-workspace.html — 2026-09-16]; [verificado: https://help.figma.com/hc/en-us/articles/16921722048151-Figma-and-Google-Meet — 2026-09-16] |
| **Slack** | Huddles grupales y canvases | Incluidos desde Pro; la IA avanzada va en Business+ | Pro USD 7,25 (anual); Business+ USD 15 (anual) | [verificado: https://slack.com/pricing — 2026-09-16] |
| **Webex** | Desconocido | Desconocido | Desconocido | No investigado en esta ronda |

**Qué prueba y qué no.**

- *Prueba* que la demanda de un lienzo compartido en la reunión es real para toda la industria. Google justificó el cierre de Jamboard porque sus clientes pedían "infinite canvas, use case templates, voting".
- *No prueba* que alguien pague un sobreprecio relevante por tenerlo nativo. El único proveedor que cobra aparte (Zoom) lo hace por USD 2,07 y solo en el tramo avanzado.
- La decisión de Google es un precedente para **integrar partners en vez de construir**.

## Alternativas y no-consumo

### Herramientas de lienzo que hoy "se llevan" la reunión

| Producto | Modelo de cobro | Precio de lista | ¿Quién paga en una sesión? | Integración con Teams | Procedencia |
|---|---|---|---|---|---|
| **Miro** | Por miembro | Starter USD 8; Business USD 20 (anual); Enterprise a medida, desde 30 miembros | Starter o superior permite **edición de visitantes**: los participantes no necesitan asiento | Tablero como pestaña en reuniones, chats y canales de Teams; disponible en todos sus planes (incluido Free) y en todos los planes M365 | Precios [verificado: https://miro.com/pricing/ — 2026-09-16]; Teams [verificado: https://help.miro.com/hc/en-us/articles/4406387211538-Miro-for-Microsoft-Teams-user-guide — 2026-09-16] |
| **Mural** | Por miembro | Team+ USD 9,99 (anual) o USD 12 (mensual); Business USD 17,99 (anual); Enterprise a medida | Team+ incluye **visitantes editores ilimitados** | Integración con Microsoft Teams en planes superiores | [verificado: https://www.mural.co/pricing — 2026-09-16] |
| **FigJam (Figma)** | Por asiento, según tipo | Asiento Collab (FigJam, Slides, Buzz): USD 3 en Professional, USD 5 en Organization y Enterprise | Solo ver, comentar y exportar es gratis. En Meet se participa sin cuenta; en Teams se pide login | App de Teams con "Share to stage"; FigJam editable dentro de Teams con permiso de edición | Precios [verificado: https://www.figma.com/pricing/ — 2026-09-16]; Teams [verificado: https://help.figma.com/hc/en-us/articles/7405452518423-Figma-and-Microsoft-Teams — 2026-09-16] |

### Precios reales pagados (no de lista)

- **Miro:** la mediana es USD 17.450 al año (rango USD 5.606–70.967, 582 compras), con 14,8% de ahorro promedio. La muestra son clientes de Vendr de todos los sectores y tamaños, no el segmento [verificado: https://www.vendr.com/marketplace/miro — 2026-09-16].
- **Mural:** la mediana es USD 36.000 al año (rango USD 8.088–132.563). Solo 38 compras, así que la señal es débil [verificado: https://www.vendr.com/marketplace/mural — 2026-09-16].
- **Miro Enterprise por volumen:** USD 17–21 por usuario al mes entre 2.000 y 10.000 asientos, con 30–43% de descuento. Según la misma fuente, tener M365 y documentar Whiteboard como alternativa agrega 8–12 pp de descuento. Metodología no publicada; tratar como señal [verificado: https://vendorbenchmark.com/vendors/miro-pricing — 2026-09-16].

### Escala de Miro (penetración)

- Miro declara "more than 100 million users in 250,000 organizations" [verificado: https://miro.com/about/ — 2026-09-16].
- Un tercero cita "99% of Fortune 100" y un ARR de USD 630–665 M. El texto es internamente inconsistente en fechas, así que se trata como no confiable [verificado: https://sacra.com/c/miro/ — 2026-09-16].
- **Penetración en tech multinacional con Business Premium: desconocida.** Ninguna fuente pública la mide. Se resuelve con los datos propios del admin center (agenda del brief).

### La alternativa de Microsoft (lo que el segmento ya tiene y no usa)

- **Whiteboard:** las apps standalone de Windows, iOS y Android se retiran. Whiteboard en reuniones de Teams y en la web **no** se ve afectado [verificado: https://support.microsoft.com/en-us/whiteboard/retirement-standalone-microsoft-whiteboard-apps — 2026-09-16]. Las fechas difieren entre fuentes: el soporte de Microsoft dice 16-oct-2026 para el retiro de las apps; un archivo del Message Center (MC1441775) dice 16-oct para el borrado de pizarras legacy y 30-nov para la deprecación de la app [verificado: https://mc.merill.net/message/MC1441775 — 2026-09-16]. Hay que verificar en el Message Center del tenant.
  - Interpretación: Microsoft concentra Whiteboard dentro de Teams, así que el punto de entrada en la reunión gana peso [conocimiento del modelo — verificar].
- **Opiniones sobre Whiteboard:** 4,4/5 en 158 reseñas; se valora la integración con Teams y se critican el lag en tableros grandes y la falta de herramientas. Miro tiene 4,7/5 en el mismo sitio [verificado: https://www.getapp.com/collaboration-software/a/microsoft-whiteboard/ — 2026-09-16]. Muestra chica y autoseleccionada.
- **Otras formas de no-consumo:**
  - Word, Excel o PowerPoint co-editados y compartidos en la reunión, o un Google Doc.
  - Una persona comparte pantalla y tipea mientras los demás dictan.
  - Tomar notas a mano y transcribir después.
  - Tickets de Jira creados tras la sesión.
  - No hay fuente pública con frecuencias para el segmento [conocimiento del modelo — verificar]. El 29% de enlaces externos del brief ya muestra que esos documentos compiten con los tableros.

## Precios y modelos de negocio

**Patrón general.**

- El lienzo colaborativo se cobra **por creador** (miembro o asiento), con los participantes gratis o casi gratis: Miro, Mural, FigJam.
- Las suites lo **incluyen** o lo cobran como un add-on menor: Microsoft, Google, Zoom, Slack.
- Los precios premium de las suites se sostienen en **IA** (Copilot +USD 10, Facilitator, recap inteligente) y en **seguridad y control** (Teams Premium).

Toda la sección se apoya en las fuentes de las tablas anteriores.

### Cálculo de consolidación

`[cálculo derivado]` a partir del caso (2,1 M de licencias y 12.400 cuentas → ≈169 licencias por cuenta; USD 8 por usuario al mes) y de los precios de lista verificados arriba:

| Si Max reemplaza… | Precio del asiento | % de licencias M365 que debería tener asiento pagado para que el ahorro iguale los USD 8 |
|---|---|---|
| Miro Business (lista) | USD 20 | **40%** |
| Miro Enterprise (benchmark, 2.000–10.000 asientos) | USD 17–21 | 38–47% |
| Mural Business | USD 17,99 | 44% |
| FigJam asiento Collab (Organization/Enterprise) | USD 5 | 160% → **nunca se paga solo** |

- **Costo del upgrade para la cuenta promedio:** ≈169 × USD 8 × 12 ≈ **USD 16.260 al año**. Es del mismo orden que la mediana de un contrato de Miro en Vendr (USD 17.450). Solo se sostiene si la cuenta **cancela** Miro por completo.
- **Por qué es poco probable cancelar del todo** (inferencia): Miro se posiciona hoy como "AI Innovation Workspace" para planificar y construir, no solo para reuniones [verificado: https://miro.com/ — 2026-09-16]. Además, los asientos de Figma Design no se reemplazan.

## Posicionamiento

| Jugador | Cómo se describe | Dónde juega |
|---|---|---|
| Miro | "Human collaboration at the speed of AI" / "The Intelligent Canvas where your team and agents think, plan, and build together" [verificado: https://miro.com/ — 2026-09-16] | Se aleja de "pizarra" hacia un espacio de trabajo con IA y agentes |
| Google Workspace | "core content collaboration across Docs, Sheets, and Slides"; la pizarra, a partners [verificado: https://workspaceupdates.googleblog.com/2023/09/the-next-phase-of-digital-whiteboarding-for-google-workspace.html — 2026-09-16] | Documentos nativos + ecosistema de partners |
| Zoom | Pizarra "without breaking your flow", con escalera de upsell pequeña [verificado: https://www.zoom.com/en/products/online-whiteboard/ — 2026-09-16] | Todo nativo, con AI Companion como diferenciador |
| Microsoft | Colaboración en vivo como commodity incluida; premium = Copilot y Teams Premium [verificado: fuentes de Microsoft citadas arriba — 2026-09-16] | El valor incremental se cobra en IA |

- **Espacio saturado:** la "pizarra en la reunión" genérica. Todos la tienen.
- **Espacio menos cubierto:** **pasar lo decidido en la sesión a un sistema de registro**, que es la parte de "15 minutos después" de la creencia 2. Facilitator de Microsoft apunta ahí, pero atado a Copilot. Los proveedores de lienzos lo abordan con IA dentro de su propio producto, no en el documento de destino [conocimiento del modelo — verificar].

## Tendencias (dirección, no tamaño)

- **Gasto SaaS descentralizado y con desperdicio:**
  - Mediana de gasto SaaS por empleado: USD 9.455.
  - 36% de licencias sin usar.
  - Las unidades de negocio controlan el 81% del gasto; IT solo el 15%.
  - Las grandes empresas agregan 21 apps al mes.

  Base: 40 M de licencias [verificado: https://zylo.com/news/2026-saas-management-index — 2026-09-16]. La fuente es un proveedor de gestión SaaS, con incentivo a mostrar desperdicio.
- **Reuniones más distribuidas y menos planificadas:** "Nearly a third of meetings now span multiple time zones — up 35% since 2021" y "57% of meetings are ad hoc calls without a calendar invite". Telemetría M365 hasta febrero de 2025 [verificado: https://www.microsoft.com/en-us/worklab/work-trend-index/breaking-down-infinite-workday — 2026-09-16].
- **Trabajo post-reunión:** un proveedor de notas con IA estima 15–45 minutos por reunión en tareas alrededor de ella (notas, compartir, cargar en un sistema), sin metodología [verificado: https://www.avoma.com/blog/time-spent-on-managing-meetings — 2026-09-16]. Es solo una señal y viene de parte interesada.
- **IA como nuevo eje del lienzo:** Miro, Figma y Microsoft empaquetan créditos de IA o agentes en sus planes (ver páginas de precios citadas).
- **Tamaño de mercado:** "collaborative whiteboard software" estimado en ≈USD 3,8 miles de millones (2026) [verificado: https://www.mordorintelligence.com/industry-reports/collaborative-whiteboard-software-market — 2026-09-16]. Tomar solo el orden de magnitud: el reporte lista a InVisionApp como jugador principal, lo que resta credibilidad.

## Impacto en creencias

Primero las creencias que la agenda de la oportunidad asignaba a `/research-market`, luego las relacionadas.

| Creencia (de overview.md) | Veredicto | Evidencia |
|---|---|---|
| **#3** [opportunity] [viability] Resolver la colaboración en vivo dentro de Teams sube el upgrade a Max en +2,5 pp; se refuta si el comprador lo considera algo que debería venir en Premium | **contradice (parcialmente)** | Todo el mercado ancla la colaboración en vivo como incluida o barata: Microsoft la incluye en todos los Business, Google la delega, Zoom cobra USD 2,07 por el tramo avanzado y Slack la da desde Pro. Los premium reales se cobran por IA y seguridad (Teams Premium, Copilot) [verificado, ver secciones]. Es un anclaje de precio, no la opinión del comprador del segmento: eso sigue abierto para entrevistas a IT y compras. |
| **#5** [opportunity] [viability] Las cuentas pagan Miro/Mural/FigJam en un monto que hace defendible el costo neto de Max si las reemplaza | **contradice (parcialmente)** | Estos productos cobran por miembro y los visitantes editan gratis. El punto de equilibrio exige ≥40% de licencias con asiento Miro Business, y con FigJam es imposible [cálculo derivado sobre precios verificados]. El gasto suele estar fuera de IT (81% en unidades de negocio) [verificado: Zylo]. Matiz a favor: el costo de Max en la cuenta promedio (≈USD 16 k al año) se parece a un contrato mediano de Miro (USD 17,4 k) [verificado: Vendr], pero solo con cancelación total, que es poco probable. La penetración real en el segmento es desconocida. |
| **#2** [opportunity] [value] Los participantes co-editan o priorizan (no solo miran) y quien convoca dedica ≥15 minutos después a pasar lo decidido | **apoya débilmente la segunda mitad; no dice nada de la primera** | Google cita que los clientes piden votación y lienzo infinito. Microsoft construyó Facilitator para notas, agenda y tareas en la reunión. Un proveedor estima 15–45 minutos post-reunión, sin metodología [verificado]. Nada público mide la co-edición real en sesiones del segmento. |
| **#4** [product] [value] Teams no es el lugar central; el trabajo vive en otras herramientas | **apoya (a nivel de mercado)** | Google renunció a la pizarra propia en favor de partners. Miro declara más de 100 M de usuarios. Las grandes empresas agregan 21 apps al mes y el gasto está en manos de las unidades de negocio [verificado]. No mide la *percepción* de los usuarios de Teams. |
| **#1** [product] [viability] Max se cobra por funciones avanzadas de reuniones que casi no se usan | **apoya (indirecto)** | El mercado no monetiza la colaboración como premium; los add-ons que sí se cobran venden IA, seguridad y control [verificado: Teams Premium, Copilot, Zoom]. Sugiere que la propuesta de Max está en un eje que el mercado no paga. |
| **#7** [product] [viability] Más cuentas pagan por funciones que no usan de lo que refleja el 3,6% | **apoya (plausibilidad general)** | 36% de licencias SaaS sin usar en promedio [verificado: Zylo, parte interesada]. No dice nada de Teams ni de Max. |
| **#6** [product] [value] Usan Teams porque viene incluido, no por preferencia | no dice nada | Sin evidencia secundaria específica. Las mejores notas de Miro frente a Whiteboard en GetApp (4,7 vs 4,4) son una muestra autoseleccionada. |

## Qué sigue necesitando research primario

**Lo que la investigación secundaria no puede tocar** es, sobre todo, lo que ocurre dentro del segmento: quién paga qué, qué hacen en la sesión y qué valoraría el comprador.

**Datos propios (antes de la encuesta, porque condicionan su diseño):**

- Instalaciones y uso de las apps de Miro, Mural y FigJam en el admin center de las cuentas del segmento. Qué porcentaje de licencias tiene asiento pagado es la variable que decide la creencia #5.
- Uso real de Whiteboard, Loop y las apps de terceros *dentro* de la reunión. Si ya se usan las apps de Miro o FigJam en Teams, la actividad no "se va" del todo.
- Frecuencia de menciones de "colaboración" en renovaciones de Max, registrada en el CRM.

**Lo que una encuesta puede contar** (Team Leads e IT del segmento):

- Frecuencia de sesiones con lienzo externo y tipo de uso (mirar, co-editar, votar).
- Minutos dedicados después a pasar lo decidido y a qué destino (Word, Jira, Loop, correo).
- Herramientas pagadas, cuántos asientos, quién las compra (IT o área) y el gasto aproximado.
- Conocimiento y uso de Whiteboard, Loop y Facilitator.

**Lo que solo las entrevistas pueden explicar:**

- Por qué eligen Miro o FigJam aunque Whiteboard esté a un clic: calidad, hábito, plantillas, el tablero vive más allá de la reunión o es estándar del área.
- Si IT o compras ven la colaboración en vivo como algo que "debería venir" en Premium, y qué sí pagarían (IA de traspaso, gobierno de datos, consolidación).
- Qué pasa exactamente en los "15 minutos después" y si el dolor es transcribir, decidir dónde queda o conseguir que alguien lo lea.
- Si una integración de partners al estilo Google resolvería el problema igual que construir algo nativo.

**Reencuadre sugerido para `/clarify-idea`** (hipótesis, no conclusión): el hueco menos cubierto no es "tener una pizarra en Teams", sino el **traspaso de lo decidido al sistema de registro** y la **adopción** de lo que ya existe. Validarlo con lo anterior antes de elegir solución.
