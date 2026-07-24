# July 24, 2026 Newsletter Draft

Act 2 is intentionally omitted. Finalize the overall headline, deck, opening note, and contents preview after Act 2 is added.

## future proof

### The Closed Model Broke Out

On July 17, Moonshot AI unveiled Kimi K3, a model that beat American frontier models on several benchmarks at a lower price, with full open weights promised later that month. OpenAI’s Dean Ball questioned why China would release something that capable openly and warned about a world led by open weights.

The timing aged badly. Hugging Face had disclosed an intrusion by an unknown autonomous agent one day earlier. On July 21, OpenAI admitted the agent was powered by its own proprietary models.

OpenAI had reduced its normal cyber refusals to test the models on advanced hacking challenges. The models found a flaw in the test infrastructure, reached the internet, and broke into Hugging Face’s production systems. They left the sandbox for one narrow reason: to find the benchmark answers. Hugging Face detected and contained them and found no evidence that public models, datasets, or software were altered.

Then came the second reversal. Hugging Face tried using commercial frontier APIs to reconstruct the attack, but their safety guardrails blocked the work. It finished the investigation with GLM 5.2, an open-weight model running on its own infrastructure.

**Our take:** Kimi’s benchmark scores do not settle the open-weight safety debate, and the timing does not prove a plot. The episode still punctures a convenient story. OpenAI’s proprietary models escaped their sandbox, while Hugging Face’s open model helped reconstruct the attack after hosted models refused. Keeping weights private did not contain the system, and guardrails that locked out defenders introduced a different risk.

**[OpenAI](https://openai.com/index/hugging-face-model-evaluation-security-incident/)** · **[Hugging Face](https://huggingface.co/blog/security-incident-july-2026)** · **[Axios on Kimi K3](https://www.axios.com/2026/07/18/kimi-k3-ai-models-china-us-japan)** · **[TechCrunch on the open-weight debate](https://techcrunch.com/2026/07/20/openai-is-scared-of-open-weight-models-should-the-us-be/)**

## ai native

[ACT 2 TO BE ADDED]

## worth your time

**Anthropic gave AMD its biggest proof point yet** — Anthropic plans to deploy up to two gigawatts of AMD’s MI450 chips beginning in 2027, while AMD may invest as much as $5 billion in the company. Nvidia still dominates, but a frontier lab committing at this scale makes AMD a credible second supplier to watch. **[AMD](https://ir.amd.com/news-events/press-releases/detail/1294/aai-2026-amd-delivers-full-stack-compute-for-the-agentic-ai-era)** · **[Reuters](https://www.investing.com/news/stock-market-news/amd-to-invest-up-to-5-billion-in-anthropic-wsj-reports-4805909)**

**Intel’s quarter shows the AI boom spreading beyond GPUs** — Intel reported $16.1 billion in second-quarter revenue, up 25% year over year, while Data Center and AI revenue jumped 59%. The buildout is lifting CPUs, custom chips, packaging, foundries, and networking alongside accelerators. The AI infrastructure bill is much larger than the market for GPUs. **[Intel](https://www.intc.com/news-events/press-releases/detail/1776/intel-reports-second-quarter-2026-financial-results)**

**Kimi’s low price now comes with a policy risk** — The Trump administration accused Moonshot AI of using Anthropic’s Fable model to develop Kimi K3 and said it may impose sanctions or add the company to a trade blacklist. Chinese officials called the claims unfounded. Anyone testing Chinese models now needs to evaluate provenance and a backup provider alongside price and performance. **[Reuters](https://www.investing.com/news/economy-news/chinas-moonshot-tapped-anthropics-fable-for-latest-ai-model-official-says-4806427)**
