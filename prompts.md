1.Crear archivo de prompt
2. Crear index.html 
3. Crea la estructura  de un dashboard para organizar 
datos solo usando html semántico (no uses otros frameworks, solo html puro), considerar schema.org y accesibilidad y que sea mobile first UTILIZANDO UNICAMENTE TAILWIND(NO MEZCLAR CON OTRA LIBRERIA) para los estilos:
Considera la siguiente información para crear datos en base a ello:
a. Objetivo:
Una influencer fitness que se dedica al crossfit,  está empezando a relacionarse con marcas como reebok, nobull, nike etc. necesitamos medir el impacto de sus anuncios y su conversión.
El problema es que tiene múltiples cuentas en redes sociales (Instagram, TikTok, YouTube, etc.)
Se requiere un reporte claro para supervisar negocio sin perder datos precisos entre las múltiples plataformas
Que muestre lo más importante para tomar decisiones rápidas.

b. Preguntas a considerar:
     - ¿Cuánto dinero estoy generando en comisiones?
     - ¿Qué productos están generando más ingresos?
     - ¿Qué tan bien convierten mis anuncios (conversiones / alcance)?
     - ¿Qué plataformas están generando mejor retorno (ingresos/costes)?
     - ¿Cuál es el engagement rate por plataforma y por producto?
c. Contexto:
Tiene 3 productos que promociona con tres precios distintos (Producto A: 50€, Producto B: 120 €, Producto C: 80 €)
Por cada venta generada recibe una comisión del 15%.

d.Tomar en cuenta:
- la estructura de landing page - el dashboard debe usar charts diversos para métricas, con visualización fácil y clara.

4. PASOS DE CREACIÓN:
a. enfocate en el layout principal: header con sidebar de información y organizar en bloques:
detalle de bloques:
1️⃣ Bloque superior: Indicadores principales del resultado (KPI):
Volumen: ventas, inscripciones, usuarios activos, impresiones
Ingresos: revenue (comisiones, ventas), MRR (facturación mensual recurrente en suscripciones), precio medio de venta
Engagement: tasa de engagement, interacciones totales, tasa de conversión
Retención: churn (tasa de bajas), permanencia, tasa de completación del proceso de venta o suscripción
Rendimiento: conversiones totales, tasa de clics (CTR), tasa de conversión
Satisfacción: puntuación de lealtad (NPS), puntuación de satisfacción (CSAT)
Eficiencia: coste por resultado, margen, tiempos

2️⃣ Bloque intermedio: “Drivers” (factores que explican el resultado):
Conversión por etapas (funnel de ventas)
Rendimiento por plataforma (Instagram, TikTok, YouTube, etc.)
Calidad (ratio de leads cualificados, attendance rate, pass rate)
Rendimiento por producto (qué producto genera más comisiones y mejor conversión)
Actividad (posts publicados, stories, reels, videos por plataforma)
Engagement (me gusta, comentarios, compartidos, guardados por plataforma)

3️⃣ Bloque inferior: Detalles operacionales (tablas/listados, alertas):
Tabla de productos: precio, comisiones generadas, conversiones, ROI por producto
Tabla de plataformas: alcance, engagement, conversiones, mejor plataforma por métrica
Tabla de campañas: fechas, productos promocionados, resultados, rendimiento
Alertas: caídas fuertes en conversión, picos de conversión, anomalías en el rendimiento
Listados con filtros: “top productos”, “top plataformas", "top campañas", "oportunidades de mejora”

b. notas diseño:
 - Piensa en componentes reutilizables como cards, botones,  tablas, widgets  etc.
Utiliza mobile-first con breakpoints tailwind - sm, md y lg.
- usa secciones y html semántico.
- para la priorización de datos dale importancia a la jerarquía visual y legibilidad, haz ÉNFASIS en los datos positivos,
- da notas de alerta a las cosas donde hay que poner ojo, agrega iconos y formas visuales que llamen la atención a lo positivo y negativo.

- para KPIs o divers utiliza chart css (SOLO CSS)

- recuerda reutiliza patrones

- utiliza un estilo minimalista y limpio, con base de blancos y trnaspareicas y degradados en los componentes, utiliza
- El color negro como contrastante a las transparencias, recuerda el contexto que es influencer fitness y de crossfit para que agregues estilos relacionados.
  
c. IMPORTANTE: 
Crear todo por bloques, detente y permíteme ir visualizando por etapas, revisar y poder ir haciendo commits por fases, fragmentala
en:
- creación de layout y estilos básicos.
- bloque 1
- bloque 2
- bloque 3
- profundiza en estilos
