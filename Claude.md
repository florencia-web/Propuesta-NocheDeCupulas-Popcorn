# CLAUDE.md — Proyecto Noche de Cúpulas (Popcorn)

> Contexto y reglas para trabajar los entregables de la propuesta comercial que Popcorn le va a presentar a Noche de Cúpulas. Leer completo antes de producir cualquier documento, auditoría o pieza. El objetivo del proyecto es entregar valor real y medible, sin sobrevender: Popcorn tiene que quedar bien porque trae un resultado concreto, no porque promete de más.

---

## 1. Contexto del proyecto

**Cliente:** Noche de Cúpulas — productora de activaciones culturales en lugares históricos (evento mensual con propuesta artística + gastronómica). Existe desde 2018. 12 ediciones principales por año + ciclos y corporativos aparte. Mismo formato; cambian locación, propuesta artística y gastronómica.

**Agencia:** Popcorn (agencia de marketing y comunicación digital, Buenos Aires). Contacto inicial lo tuvo Demian con un socio del cliente. Sol armó el cuestionario y el primer borrador de propuesta. Florencia (Operaciones) lidera el análisis y la definición del alcance.

**Objetivo declarado por el cliente:** más asistentes y más notoriedad / mayor alcance.

**Objetivo real del proyecto (nuestro):** ordenar y medir el embudo que ya tienen para que crezcan de forma rentable, antes de sumar gasto en canales nuevos.

---

## 2. El cliente en datos (fuente: cuestionario respondido + notas de Demian)

**Capacidad y demanda**
- Venden 400 en temporada baja, 600+ en alta. **Ese número es el límite de venta, NO el límite físico.** Pueden vender más.
- Pueden escalar oferta: de 1 edición mensual a hasta 4 ediciones mensuales si hay demanda.
- Suelen agotar; agotan la semana previa al evento.

**Embudo (últimos 30 días)**
- ~1.500 mensajes entrados por anuncio de Meta.
- 438 entradas vendidas (no todas salen de esos mensajes; parte viene del mailing a la base).
- No saben por qué la gente consulta y no compra.
- Seguimiento a la consulta solo cuando avanza un paso más allá de la consulta inicial.
- WhatsApp es el canal principal de comunicación. 1 sola persona atendiendo, 24 h. Reciben cientos por día.
- Objeciones: precio (poco frecuente), expectativa de otro tipo de evento, y algunos (cada vez menos) creen que es gratis.

**Público**
- Multigeneracional, últimamente mucho público 55+. Promedio 55-65. Van en parejas y grupos.
- ~30% ya vino antes / ~70% primera vez. Encuestas: 40%+ llegó por IG, 30% ya vino (también llegó por IG), resto otros.

**Base de datos**
- 16.000 registros con mails y teléfonos.
- CRM = Excel. Base gestionada con Envialo Simple + planillas de Drive. Exportan compradores de Passline. Solo automatizan la venta vía Passline.

**Canales de venta**
- Transferencia bancaria + ticketeras. La venta se reparte entre transferencias directas, Passline y Alternativa Teatral. Sin reservas.
- No tienen web propia. Compran en Passline o por link que les pasan por WhatsApp.

**Meta Ads (lo manejan ellos)**
- Objetivo de campaña: siempre "Mensajes".
- Sin Pixel. Sin remarketing (nunca probaron). Audiencias por Advantage; hace tiempo no configuran públicos.
- Una sola campaña non-stop; actualizan info + una pieza. Los reels tienen muy buena respuesta.
- **De creativo dicen que están bien; están orgullosos de cómo manejan Meta.** (Ojo político, ver Guardrails.)

**Google:** nunca hicieron Google Ads.

**Inversión (según Demian):** ~1M en Meta + ~1M en pauta tradicional (radio, etc.). La pauta tradicional hoy es 100% inmedible.

**Otras oportunidades**
- Sponsors: sí. Entradas corporativas: no, pero lo consideran. Eventos privados: sí.
- Alianzas: hoteles (sin resultados), turismo (puntual), Santander (fue sponsor), getnet (flojo).

**Benchmark que usa el cliente como referencia:** https://www.instagram.com/candlelight.concerts/
**Cuenta del cliente:** https://www.instagram.com/nochedecupulas/

---

## 3. Diagnóstico estratégico (NO perder de vista al producir entregables)

El cliente pregunta "¿dónde invierto más para traer más gente?". Los números dicen otra cosa: **el problema no es de demanda, es de conversión, medición y retención.** Entran ~1.500 consultas y se caen ~2/3, nadie sabe por qué, y a esa gente no se la vuelve a tocar. No les falta gente arriba del embudo: se les escapa la que ya llega y no pueden medir nada.

Por eso el trabajo NO arranca por sumar canales (Google/programática). Arranca por **poner medición + recuperar lo caliente que ya tienen.** Todo entregable debe reforzar ese marco: pasamos de "¿qué canal agrego?" a "¿cómo hago rentable y medible lo que ya funciona?".

Insight clave para el proyecto: **el Pixel de Meta SÍ se puede instalar en Passline** (verificado en la documentación de Passline: desde el perfil de organizador → Mis Eventos → "Pixel Meta"; GA4/GTM se piden al ejecutivo de cuenta). Esto significa que se puede medir y hacer remarketing **sin necesidad de landing para empezar**. Es el desbloqueo barato y demostrable que hace creíble toda la propuesta.

---

## 4. Alcance a cotizar — PROYECTO PUNTUAL

Cotizar como proyecto cerrado (one-time). La gestión mensual se ofrece después (ver sección 5).

### 4.1 Auditoría de campañas + revisión de medición
- Revisar el esquema actual de campañas de Meta (estructura, objetivo, públicos, piezas) y documentar oportunidades de mejora concretas.
- Diagnóstico del estado de medición y plan para dejarlo funcionando: instalar Pixel de Meta + GA4 (arrancando sobre Passline, que lo permite), definir eventos clave y baseline real del embudo.
- Entregable: informe de auditoría + plan de medición + baseline. Framing honesto: es la base sobre la que se apoya todo lo demás.

### 4.2 Landing / One Page para capturar tráfico
- One page propia para capturar tráfico, medir y remarketear.
- **Framing obligatorio: la landing NO reemplaza a Passline.** El checkout sigue en Passline (Alternativa Teatral / transferencia según corresponda); la landing sirve para ser dueños del dato, medir intención y alimentar públicos. El cliente hoy cree que no puede tener landing "porque no tiene estructura comercial" — es un malentendido, hay que corregirlo con cuidado: la landing deriva a Passline, no cobra por sí sola.
- Es correcto ubicarla como fase 2 respecto de la medición: primero pixel en Passline, después landing.

### 4.3 Remarketing + audiencias Lookalike (handoff)
- Configurar campañas/audiencias de remarketing (público más caliente que hoy no tocan: quienes vieron la página de compra y no completaron).
- Configurar audiencias Lookalike. **Nota técnica: la base de 16.000 se puede subir como público personalizado y generar Lookalikes desde el día 1**, sin esperar a que el pixel acumule datos.
- Modelo de entrega: **dejarlas configuradas y documentadas para que el cliente las use cuando quiera** (playbook de uso). Requiere acceso al Business Manager / cuenta publicitaria del cliente — confirmar acceso antes de cotizar tiempos.

### 4.4 Auditoría de redes sociales (agregar al proyecto)
- El cliente toma como referencia a Candlelight (candlelight.concerts). Usar esa cuenta como benchmark y mostrarle, lado a lado, cómo está estructurada y la imagen profesional que transmite vs. su cuenta actual.
- Dimensiones a evaluar en @nochedecupulas contra el benchmark:
  1. Coherencia de grilla e identidad visual (¿se ve un sistema o posteos sueltos?).
  2. Sistema de plantillas consistente (tipografía, diagramación por tipo de pieza).
  3. Calidad fotográfica / render de la experiencia (Candlelight es muy cinematográfico y cálido; alta consistencia).
  4. Jerarquía y claridad de la info del evento (qué / dónde / cuándo / link).
  5. Uso de Reels como prueba social de la experiencia en vivo.
  6. Bio y links optimizados para conversión.
- Entregable: auditoría con oportunidades de mejora priorizadas (no rehacer la marca, señalar el gap y el camino). Framing respetuoso: no decirles que están mal, mostrar el estándar al que pueden subir.

---

## 5. Fase siguiente — GESTIÓN MENSUAL (upsell, no incluir en el proyecto inicial)

Identificado como alto valor pero se ofrece después de mostrar resultado con el proyecto:
- **Recuperación de consultas de WhatsApp:** proceso + automatización liviana para los ~1.000 que consultan y no compran. Recuperar 10-15% ≈ 100-150 entradas/mes ≈ casi una edición extra.
- **Base de 16k (lifecycle/CRM):** preventa a la base antes de gastar en pauta fría, reactivación de los que no vuelven, segmentación por frecuencia. Margen alto: le hablás a gente que ya te conoce.
- **Optimización continua de Meta** y gestión de las audiencias ya configuradas.
- **Monetización:** entradas corporativas, paquetes de sponsor, tier premium (evento que agota = monetizar mejor cada función, no solo vender más tickets).

---

## 6. Guardrails de honestidad (aplican a TODOS los entregables)

- **No sobrevender Google Ads.** Para este caso sirve casi solo como defensa de marca (búsquedas de "Noche de Cúpulas"): barato pero poca gente y ya te conocen. Search de categoría es caro, competido y de baja afinidad con un nicho 55-65. Presentarlo como prueba chica, nunca como motor de crecimiento.
- **No prometer programática.** Es el canal más difícil de atribuir; sin medición andando es donde peor quedamos. Queda para evaluar con datos, después.
- **Landing ≠ reemplazo de Passline.** Ver 4.2. No prometer que la landing "resuelve la venta".
- **Membresía/fidelización:** válido a futuro, no prioridad para un evento mensual que ya agota. No cargar el proyecto inicial con esto.
- **Respeto por el manejo de Meta del cliente.** Están orgullosos y de creativo dicen estar bien. El ángulo es "ustedes captan bien; falta la infraestructura de abajo (pixel, medición, remarketing) que no se puede hacer sin la configuración técnica". Gap de infraestructura, no de talento.
- **Todo lo que se promete tiene que ser demostrable.** Preferir un primer resultado chico y probado antes que un menú grande sin baseline.

---

## 7. Datos técnicos clave

- **Pixel en Passline: sí se puede** (perfil de organizador → Mis Eventos → "Pixel Meta"; GA4/GTM vía ejecutivo de cuenta). Fuente: documentación de Passline.
- Passline reporta si el usuario compró el ticket → permite trackear conversión y armar públicos.
- Lookalikes: sembrar desde la base de 16k (custom audience) para tener alcance desde el día 1.
- Handoff de audiencias/remarketing requiere acceso al Business Manager del cliente.
- La pauta en radio (~1M) hoy es inmedible: sumar valor haciéndola medible (UTMs, códigos promo, "mencioná la radio") es parte del pitch de auditoría, aunque no se gestione el medio.

---

## 8. Tono y formato de entregables

- **Idioma:** español rioplatense, registro profesional. Noche de Cúpulas es una marca cultural con público 55-65: sobrio, cuidado, nada informal. **Sin emojis en documentos ejecutivos ni en la propuesta.**
- **Documentos para dirección/propuesta:** Word y/o PDF, prolijos, con estructura clara (diagnóstico → alcance por etapas → qué entregamos → qué NO prometemos todavía).
- **Estructura de la propuesta:** empezar por el diagnóstico (el reframe de la sección 3), después el proyecto, después mencionar la gestión mensual como continuidad. No abrir con el menú de servicios.
- Marca Popcorn cuando aplique: violeta `#6100A4` y turquesa `#00FDE2`, tipografías Bricolage Grotesque + Instrument Sans.

---

## 9. Pendientes de confirmar antes de cerrar la cotización

- Tasa de conversión exacta del embudo (hoy no la tienen; se calcula recién con el baseline).
- Montos reales de inversión mensual (Meta y radio) — los ~1M/~1M vienen de Demian, sin confirmar por el cliente.
- Acceso al Business Manager / cuenta publicitaria (necesario para 4.3).
- Si Passline permite además GA4/GTM en la instancia del cliente (pedirlo al ejecutivo de cuenta de ellos).
- Interés real en monetización corporativa/sponsors (marcaron "lo consideramos").