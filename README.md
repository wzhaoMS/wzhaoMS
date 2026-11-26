### 🖥️ Local LLM leaderboard

**[wzhaoms.github.io/local-llm-leaderboard](https://wzhaoms.github.io/local-llm-leaderboard/)** benchmarks open-weight LLMs (Qwen, GLM, DeepSeek and more) on one workstation: an RTX PRO 6000 (96 GB), an RTX 5090 (32 GB) and 128 GB of RAM. It measures quality on real work, speed, and prompts of up to 1M tokens, with Claude, GPT and Gemini as cloud references.

<a href="https://wzhaoms.github.io/local-llm-leaderboard/"><img src="assets/leaderboard.png" alt="Local LLM leaderboard home page" width="100%"></a>

#### 🚲 Each lab's strongest model draws a pelican riding a bicycle

Every model got the same prompt: *"Generate an animated SVG of a pelican riding a bicycle."* ([Simon Willison's test](https://simonwillison.net/tags/pelican-riding-a-bicycle/)). Each model's first valid try is below; [every try is on the leaderboard](https://wzhaoms.github.io/local-llm-leaderboard/#pelican).

<table>
  <tr>
    <td align="center" width="33%"><a href="https://wzhaoms.github.io/local-llm-leaderboard/#pelican"><img src="https://wzhaoms.github.io/local-llm-leaderboard/data/pelican/flashnext-q5-2gpu-medium-1.svg" width="260" alt="Pelican riding a bicycle, drawn by Qwen3.8-Flash-Next"></a><br><b>Qwen3.8-Flash-Next</b> Q5<br><sub>Qwen · local, both GPUs</sub></td>
    <td align="center" width="33%"><a href="https://wzhaoms.github.io/local-llm-leaderboard/#pelican"><img src="https://wzhaoms.github.io/local-llm-leaderboard/data/pelican/glm53flash-q2-2gpu-1.svg" width="260" alt="Pelican riding a bicycle, drawn by GLM-5.3-Flash"></a><br><b>GLM-5.3-Flash</b> Q2<br><sub>Z.ai · local, both GPUs</sub></td>
    <td align="center" width="33%"><a href="https://wzhaoms.github.io/local-llm-leaderboard/#pelican"><img src="https://wzhaoms.github.io/local-llm-leaderboard/data/pelican/deepseek41-coder-6000-2.svg" width="260" alt="Pelican riding a bicycle, drawn by DeepSeek-V4.1-Flash Coder"></a><br><b>DeepSeek-V4.1-Flash</b> Coder<br><sub>DeepSeek · local, RTX PRO 6000</sub></td>
  </tr>
  <tr>
    <td align="center"><a href="https://wzhaoms.github.io/local-llm-leaderboard/#pelican"><img src="https://wzhaoms.github.io/local-llm-leaderboard/data/pelican/inkling2mini-5090-1.svg" width="260" alt="Pelican riding a bicycle, drawn by Inkling-2-Mini"></a><br><b>Inkling-2-Mini</b><br><sub>Thinking Machines · local, RTX PRO 6000</sub></td>
    <td align="center"><a href="https://wzhaoms.github.io/local-llm-leaderboard/#pelican"><img src="https://wzhaoms.github.io/local-llm-leaderboard/data/pelican/cloud-claude-opus-55-1.svg" width="260" alt="Pelican riding a bicycle, drawn by Claude Opus 5.5"></a><br><b>Claude Opus 5.5</b><br><sub>Anthropic · cloud, effort high</sub></td>
    <td align="center"><a href="https://wzhaoms.github.io/local-llm-leaderboard/#pelican"><img src="https://wzhaoms.github.io/local-llm-leaderboard/data/pelican/cloud-gpt-6-astra-max-1.svg" width="260" alt="Pelican riding a bicycle, drawn by GPT-6 Astra"></a><br><b>GPT-6 Astra</b><br><sub>OpenAI · cloud, effort max</sub></td>
  </tr>
  <tr>
    <td align="center"><a href="https://wzhaoms.github.io/local-llm-leaderboard/#pelican"><img src="https://wzhaoms.github.io/local-llm-leaderboard/data/pelican/cloud-gemini-4-neon-xhigh-1.svg" width="260" alt="Pelican riding a bicycle, drawn by Gemini 4 Neon"></a><br><b>Gemini 4 Neon</b><br><sub>Google · cloud, effort xhigh</sub></td>
    <td align="center"><a href="https://wzhaoms.github.io/local-llm-leaderboard/#pelican"><img src="https://wzhaoms.github.io/local-llm-leaderboard/data/pelican/cloud-grok-47-1.svg" width="260" alt="Pelican riding a bicycle, drawn by Grok 4.7"></a><br><b>Grok 4.7</b><br><sub>xAI · cloud, effort medium</sub></td>
    <td align="center"><a href="https://wzhaoms.github.io/local-llm-leaderboard/#pelican"><img src="https://wzhaoms.github.io/local-llm-leaderboard/data/pelican/cloud-mai-code-2-1.svg" width="260" alt="Pelican riding a bicycle, drawn by MAI Code 2"></a><br><b>MAI Code 2</b><br><sub>Microsoft · cloud, effort max</sub></td>
  </tr>
</table>
