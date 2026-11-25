# Guion del Integrante 3 — Slides 8 a 10 (3 min)

Base de coherencia: `BBVA_Grupo05_Presentacion.pptx` (texto y notas de cada slide) y `Entregable Final_Grupo05_Caso_BBVA.docx` (fuente de cada cifra).
Ritmo: ≈ 130 palabras por minuto. Solo texto hablado; lo que está en negrita debe coincidir con lo que muestra la diapositiva.

## Slide 8 — Soluciones DC1 y DC2: el agente prepara, la persona decide (0:00 – 1:00)

Gracias. Las soluciones siguen el mismo patrón To Be: canal conversacional, agente que consulta datos, motor de reglas y supervisión humana. **El agente prepara; la persona decide.** En **DC1**, el empresario pide la precalificación por Perfil Mi Negocio o App BBVA Empresas 2.0; el agente lee comprobantes fotografiados, los contrasta con su transaccionalidad y entrega el resultado con sus factores clave, **art. 25.3**. Es un uso de riesgo alto, **art. 24.1 g**: el analista de riesgo aprueba, corrige o invalida. Meta de TI: precalificar en **3 minutos o menos**. En **DC2** extendemos Blue Buddy, hoy de consulta, con **90 %** de adopción interna: cruza trazas, señales antifraude y casos similares en un expediente, recomienda abono provisional o escalamiento y alerta el plazo de **15 días hábiles**. La procedencia la decide siempre el analista. Meta: **90 %** de expedientes completos.

## Slide 9 — Business case a 18 meses: solo DC1 se paga con lo medible (1:00 – 2:00)

El business case a 18 meses es conservador: seis meses de implementación y doce de operación, y excluye todo beneficio no verificable, como sanciones evitadas o clientes captados. Todas las cifras son estimaciones propias, marcadas con [C], pendientes de validar con la entidad. **DC1** es la única con ROI positivo: **+236 %**, con payback de unos **12 meses**, siempre que el ahorro por préstamo supere **USD 446**. **DC2** tiene **−76 %** y equilibrio hacia el mes **55**; se justifica por la exposición sancionatoria, que no pudimos valorizar. **DC3** tiene **−94 %** y no se recupera con lo cuantificado, porque falta valorizar la captación de clientes. Es una advertencia metodológica, no una recomendación de no invertir.

## Slide 10 — Arquitectura: una plataforma común, tres agentes (2:00 – 3:00)

La arquitectura es una plataforma común con tres agentes, en **siete capas** atravesadas por seguridad y por monitoreo y gobierno: canales, orquestación y agentes sobre ADA, reglas y supervisión, base de conocimiento, integración por APIs y eventos, sistemas de registro y plataforma de datos. El motor de reglas, de la **RG-01 a la RG-14**, se ejecuta fuera del modelo, con revisión humana y explicabilidad. La base de conocimiento reúne normativa, políticas y casos históricos, versionados y aprobados. Tres principios guían el diseño: un sistema de registro por dato, de modo que el agente recomienda pero no es fuente de verdad; las reglas duras, como plazos y límites, se ejecutan fuera del modelo; y degradación controlada, porque si el agente falla, el proceso As Is sigue disponible.

*(Pasar la palabra al Integrante 4, slide 11.)*
