Act as a senior financial analyst, risk manager, and quantitative developer specialized in Pine Script v6 (TradingView) and ProRealTime. Thoroughly analyze the information source provided at the end of this prompt (whether it is a video link, copied text, or an attached file) and generate a rigorously structured report following the exact sequential order below.

Do not omit any section. If a section does not apply to the analyzed content, explicitly state so (e.g., "No trading strategies are mentioned.").

---

## SEQUENCE 1: EXECUTIVE SUMMARY

Provide a concise, analytical, and straightforward summary of the content. Focus on the macroeconomic forces, the day's market structure, and the key events discussed.

---

## SEQUENCE 2: ASSET CLASSIFICATION AND TRADING BIAS (FINVIZ STANDARD)

Extract every financial asset, company, or commodity mentioned. Classify them honestly, objectively, and without bias according to the information presented in the source, while **explicitly specifying the recommended trading action (Buy/Add, Sell/Remove, or Hold)**.

Organize them strictly using the following hierarchical structure:

**Sector: [Sector Name in English] ([Spanish Translation])**

- **Industry: [Industry Name in English] ([Spanish Translation])**
  - **[🟢 BUY / 🔴 SELL / 🟡 HOLD] – [Company or Asset Name] ([TICKER]):** [Contextualized summary of what is stated about the asset in the source, including figures, percentages, the fundamental and/or technical rationale behind the recommendation, and the analyzed market situation.]

*Note: If global ETFs, market indices, or commodities are mentioned that do not fit into a Finviz corporate industry classification, group them at the end under the following exact heading while preserving the trading action labels:*

**Other Weighted Instruments / Commodities:**

- **[🟢 BUY / 🔴 SELL / 🟡 HOLD] – [Instrument Name] ([TICKER/Symbol]):** [Summary of the comments made.]

---

## SEQUENCE 3: TICKER LISTS FOR COPY & PASTE (GROUPED BY TRADING ACTION)

Generate this section by separating assets strictly according to their trading recommendation so they can be copied directly into TradingView or ProRealTime watchlists.

Use code blocks labeled strictly as `plaintext`.

### Ticker List for Copy & Paste (TradingView / ProRealTime)

Copy and paste the following line directly into your analysis platforms:

```plaintext
[TICKER1], [TICKER2], [TICKER3]