# AMD_Slingshot_hackathon

# 🛡️ SentinelAI: Phishing Intelligence System

<p align="left">
  <img src="https://img.shields.io/badge/System-Online-16a34a?style=flat-square" />
  <img src="https://img.shields.io/badge/AI-Claude_Powered-8b5cf6?style=flat-square" />
  <img src="https://img.shields.io/badge/Security-Multi--Layer-2563eb?style=flat-square" />
</p>

`SentinelAI` is a multi-layered security tool designed to detect and explain phishing threats in emails, messages, and URLs using AI-driven analysis.

---

### ✨ Key Features

* **`Dual-Engine Analysis`**: Combines local pattern matching with Claude AI for deep threat intelligence.
* **`NLP Threat Detection`**: Identifies credential harvesting, urgency, fear-based tactics, and authority impersonation.
* **`URL Risk Scoring`**: Analyzes TLDs, IP usage, domain length, and brand spoofing patterns.
* **`Visual Risk Assessment`**: Provides a `0-100` risk score with a breakdown of NLP, URL, Manipulation, and Graph Intel scores.
* **`Explainable Security`**: Offers plain-language explanations and clear recommendations for every analysis.

---

### 🛠️ How it Works

1. **Input**: `Paste` an email body or a suspicious URL into the interface.
2. **Processing**: The system runs `local heuristic checks` followed by an `AI-powered` psychological manipulation audit.
3. **Verdict**: SentinelAI generates a risk score and classifies the threat as `Safe`, `Suspicious`, or `Phishing`.
4. **Network Graph**: Visualizes the relationship between the `sender`, `domain`, and `embedded URLs`.

---

### 🚀 Technical Stack

* **Frontend**: `HTML5`, `CSS3` (Sora & IBM Plex Mono fonts), `Vanilla JavaScript`.
* **AI Integration**: `Claude API` (Anthropic) for advanced classification.
* **Visualization**: `HTML5 Canvas` for threat network graphing.

---

### ⚠️ Security Warning
> [!IMPORTANT]  
> This frontend implementation requires a backend proxy to securely handle API keys. Ensure `ANTHROPIC_API_KEY` is never exposed in the client-side code when deploying.
