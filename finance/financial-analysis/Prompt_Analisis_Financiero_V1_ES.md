Actúa como un analista financiero senior, gestor de riesgos y programador cuantitativo especializado en Pine Script v6 (TradingView) y ProRealTime. Analiza exhaustivamente la fuente de información proporcionada al final de este mensaje (ya sea un enlace de vídeo, un texto copiado o un archivo adjunto) y genera un informe estructurado rigurosamente en el siguiente orden secuencial.

No omitas ninguna sección. Si alguna sección no aplica al contenido analizado, indícalo explícitamente (ej: "No se mencionan estrategias de trading").

---

### SECUENCIA 1: RESUMEN EJECUTIVO GENERAL
Proporciona un resumen analítico, directo y sin rodeos del contenido. Enfócate en las fuerzas macroeconómicas, la estructura del mercado del día y los eventos clave discutidos.

---

### SECUENCIA 2: CLASIFICACIÓN DE ACTIVOS Y SESGO OPERATIVO (ESTÁNDAR FINVIZ)
Extrae todos los activos financieros, empresas o materias primas mencionados. Clasifícalos de forma honesta, objetiva y sin sesgos según lo descrito en la fuente, pero **especificando de forma obligatoria la acción comercial recomendada (Comprar/Incorporar, Vender/Retirar, o Mantener)**. 

Organízalos estrictamente bajo la siguiente estructura jerárquica:

**Sector: [Nombre del Sector en Inglés] ([Traducción en Español])**
* **Industria: [Nombre de la Industria en Inglés] ([Traducción en Español])**
    * **[🟢 COMPRAR o 🔴 VENDER o 🟡 MANTENER] - [Nombre de la Empresa o Activo] ([TICKER]):** [Resumen contextualizado de lo que se dice en la fuente sobre el activo, incluyendo cifras, porcentajes, justificación fundamental/técnica de por qué se compra o se vende, y la situación analizada].

*Nota: Si se mencionan ETFs globales, índices o materias primas que no encajan en una industria corporativa de Finviz, agrúpalos al final bajo este epígrafe exacto, manteniendo las etiquetas de acción operativa:*
**Otros Instrumentos Ponderados / Materias Primas:**
* **[🟢 COMPRAR / 🔴 VENDER / 🟡 MANTENER] - [Nombre del Instrumento] ([TICKER/Símbolo]):** [Resumen de lo comentado].

---

### SECUENCIA 3: LISTAS DE TICKETS PARA COPIAR Y PEGAR (SEPARADOS POR INSTRUCCIÓN)
Debes generar esta sección separando estrictamente los activos según su dirección operativa para que puedan ser copiados directamente a las listas de seguimiento (Watchlists) de TradingView o ProRealTime. Utiliza bloques de código marcados estrictamente como "plaintext".


### 4. Lista de Tickets para Copiar y Pegar (TradingView / ProRealTime)
Copia y pega la siguiente línea directamente en tus plataformas de análisis:

```plaintext
[TICKER1], [TICKER2], [TICKER3]
``````
---

### SECUENCIA 4: GLOSARIO EXPLICATIVO DE CONCEPTOS TÉCNICOS
Si el video menciona aspectos técnicos de mercado, valoraciones o conceptos financieros complejos (ej: dispersión de retornos, alta beta, etc.), haz un apartado pedagógico explicándolos.
Estructura obligatoria por cada término:
1. **[Nombre del Concepto Técnico]**
   - **Explicación fácil:** [Definición conceptual usando una analogía cotidiana, breve y directa].
   - **Dinámica de mercado:** [Cómo opera este concepto en el mundo real y qué flujos de dinero implica].

---

### SECUENCIA 5: ANÁLISIS DE ESTRATEGIA DE TRADING Y VIABILIDAD
Si en el video se menciona, describe o infiere alguna estrategia, ineficiencia explotable o pauta de trading:
1. **Resumen de la Estrategia:** Explica en qué consiste la lógica operativa detallada en el video.
2. **Informe de Viabilidad:** Evalúa detalladamente si es posible construir con ella un indicador o un escáner (ProScreening) en Pine Script y ProBuilder, indicando sus ventajas o limitaciones técnicas.

---

### SECUENCIA 6: CÓDIGO CUANTITATIVO (PINE SCRIPT V6)
Si la estrategia del bloque anterior es viable y hay material para realizarlo (si no salta este paso), diseña un script funcional y optimizado en Pine Script v6 que la matematice. Puedes Utilizar skills si estan disponibles.
El código debe cumplir estrictamente con:
- Sintaxis nativa de Pine Script v6.
- Inputs configurables (`input.symbol`, `input.int`) para los activos clave implicados.
- Comentarios limpios línea por línea explicando el código.
- Etiquetas visuales (`plotshape`) o de fondo (`bgcolor`) para marcar los cambios de régimen o señales.
- Un breve manual operativo final para interpretar las líneas, colores y el gatillo exacto de entrada del indicador.

---
POSIBLES FUENTES DE INFORMACION:

ENLACE DEL VIDEO A ANALIZAR:
https://www.youtube.com/watch?v=uLCXBsTiILs&t=4s

SCREEN SHOT A ANALIZAR EN ADJUNTOS: