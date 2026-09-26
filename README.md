<p align="center">
  <img src="assets/header.svg" width="100%" alt="Chingangbam Deepak Angom, ML / AI engineer: LLM infrastructure and UK grid forecasting">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/deepak-angom-ai/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Based%20in-United%20Kingdom-14264A?style=for-the-badge" alt="Based in the United Kingdom">
  <img src="https://img.shields.io/badge/Open%20to-ML%20%2F%20AI%20Engineer%20roles-1E7A4F?style=for-the-badge" alt="Open to ML / AI engineer roles">
</p>

## About me

- 🎓 MSc Artificial Intelligence, University of Aberdeen (2025–2026).
- ⚡ Electrical engineer (B.Tech) turned ML engineer.
- 🛠️ I build AI systems the production way: tests in CI, measured results, and a written record of every design decision.
- 🔭 Right now: an **LLM gateway** (Aegis) and **probabilistic forecasting of the GB electricity grid** (GridPulse).

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ChingangbamDpakAngom/aegis-gateway">🛡️ Aegis Gateway</a></h3>
      <p>An API gateway that sits in front of LLMs. Hashed API-key auth, a Redis + Lua token-bucket rate limiter that stays correct across instances and <b>fails closed</b> when Redis is down, and one consistent error contract. Prompt-injection screening, caching and model routing are being built in documented phases.</p>
      <p><code>FastAPI</code> <code>Redis</code> <code>Lua</code> <code>Docker</code> <code>GitHub Actions</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ChingangbamDpakAngom/GridPulse-TFT">⚡ GridPulse-TFT</a></h3>
      <p>48-hour probabilistic forecasts (q10 / q50 / q90) of GB grid carbon intensity. A TFT-lite PyTorch model exported to ONNX, served with FastAPI, with drift checks and a Streamlit dashboard that recommends low-carbon charging windows.</p>
      <p><code>PyTorch</code> <code>ONNX</code> <code>FastAPI</code> <code>Streamlit</code> <code>Time series</code></p>
    </td>
  </tr>
</table>

## Tech I work with

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,redis,docker,githubactions,linux,git&perline=9" alt="Python, PyTorch, scikit-learn, FastAPI, Redis, Docker, GitHub Actions, Linux, Git">
</p>

## How I work

- **Small, described commits.** Each change says what it does and why.
- **Decisions on paper.** Architecture Decision Records explain the trade-offs behind each design choice.
- **Proof over claims.** Every feature ships with the tests that show it works.

## Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ChingangbamDpakAngom/ChingangbamDpakAngom/output/snake-dark.svg">
    <img alt="My contribution graph, animated as a snake eating each day's commits" src="https://raw.githubusercontent.com/ChingangbamDpakAngom/ChingangbamDpakAngom/output/snake.svg">
  </picture>
</p>
