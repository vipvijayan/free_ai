# Free LLM API — Resource Directory

[![Verified](https://img.shields.io/badge/verified-2026--10--10-blue)](https://github.com/vipvijayan/free_ai)
[![Providers](https://img.shields.io/badge/providers-27-green)](https://github.com/vipvijayan/free_ai)
[![License](https://img.shields.io/badge/license-CC--BY--4.0-lightgrey)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](CONTRIBUTING.md)

A curated, verified reference of free and trial-credit LLM inference APIs. Every link points to the official provider page; every claim was checked against primary sources on **2026-10-10**.

---

## Quick Comparison

| Provider | Free Tier Type | Daily Limit (typical) | Card Required | Best For |
|---|---|---|---|---|
| [OpenRouter](https://openrouter.ai/) | Free models | 50 req / 1,000 req (with $10 top-up) | No | Model variety, easy switching |
| [Google AI Studio](https://aistudio.google.com/) | Free tier | ~20 req/day per model | No | Gemini access, high token limits |
| [NVIDIA NIM](https://build.nvidia.com/explore/discover) | Free tier | 40 req/min | No (phone verify) | Nemotron models, Open models |
| [Mistral](https://console.mistral.ai/) | Free mode | Undocumented (per-org) | No (phone verify) | Mistral models |
| [Vercel AI Gateway](https://vercel.com/docs/ai-gateway) | Free credits | ~$5/30 days | **Yes** | Vercel ecosystem, multi-provider |
| [Kilo Gateway](https://kilo.ai/docs/gateway) | Free models | 200 req/hr per IP | No | Anonymous access, zero setup |
| [OpenCode Zen](https://opencode.ai/zen) | Free models | Unlimited $0 tokens* | No (account + billing) | Coding agents, curated models |
| [Command Code](https://commandcode.ai/) | Free deal models | Model-specific | **Yes** ($10/mo min for API) | CLI + API, cheap plans |
| [Z.ai](https://z.ai/) | Free models | Unpublished | No | GLM Flash models, permanent free |
| [AIHubMix](https://aihubmix.com/models/free) | Free models | 100 req/day · 1M tokens/day† | No ($1 to unlock) | 60 models, all protocols |
| [Requesty](https://www.requesty.ai/free-models) | Free tier | 200 req/day | No | Full gateway, EU residency |
| [Nous Portal](https://portal.nousresearch.com/) | Free plan | Standard limits | No | Hermes Agent, $0 models |
| [LLM7.io](https://llm7.io/) | Free token | 100K tokens/24hr | No | Research, Codestral/GLM |
| [BazaarLink](https://bazaarlink.ai/) | Free router | Server-owned | No | Taiwan invoices, auto router |
| [Groq](https://console.groq.com/) | Free tier | 1K req/day (varies) | No | Speed, GPT-OSS, Whisper |
| [Cohere](https://cohere.com/) | Trial key | 1K req/month | No | Command/Embed, evaluation only |
| [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai) | Free allocation | 10K neurons/day | No | Edge inference, LoRA models |

\* OpenCode Zen free models are $0/token but require a billing balance on file; anonymous external calls blocked.  
† AIHubMix: 10 trial calls free; $1 top-up unlocks permanent daily quotas.

---

## Contents

- [Part One — Free Providers](#part-one--free-providers)
  - [OpenRouter](#openrouter)
  - [Google AI Studio](#google-ai-studio)
  - [NVIDIA NIM](#nvidia-nim)
  - [Mistral (La Plateforme)](#mistral-la-plateforme)
  - [Vercel AI Gateway](#vercel-ai-gateway)
  - [Kilo Gateway](#kilo-gateway)
  - [OpenCode Zen](#opencode-zen)
  - [Command Code](#command-code)
  - [Z.ai](#zai)
  - [AIHubMix](#aihubmix)
  - [Requesty](#requesty)
  - [Nous Portal](#nous-portal)
  - [LLM7.io](#llm7io)
  - [BazaarLink](#bazaarlink)
  - [Groq](#groq)
  - [Cohere](#cohere)
  - [Cloudflare Workers AI](#cloudflare-workers-ai)
- [Part Two — Providers with Trial Credits](#part-two--providers-with-trial-credits)
- [Removed / No Longer Free](#removed--no-longer-free)
- [Contributing](#contributing)
- [License](#license)
- [Changelog](#changelog)

---

## Part One — Free Providers

> Ongoing free tiers — not one-time trial credits. No credit card required to start, except where noted.

### OpenRouter

**Endpoint:** `https://openrouter.ai/api/v1/chat/completions` (OpenAI-compatible)

**Limits:** 20 req/min · 50 req/day · up to 1,000 req/day with $10 lifetime top-up ([limits](https://openrouter.ai/docs/api/reference/limits)) · No card

**Free Models** (rotating; check [model page](https://openrouter.ai/models) before relying):

| Model |
|---|
| Cohere North Mini Code |
| Poolside Laguna S 2.1 |
| Poolside Laguna XS 2.1 |
| google/gemma-4-26b-a4b-it:free |
| google/gemma-4-31b-it:free |
| nvidia/nemotron-3-nano-30b-a3b:free |
| nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free |
| nvidia/nemotron-3-super-120b-a12b:free |
| nvidia/nemotron-3-ultra-550b-a55b:free |
| nvidia/nemotron-3.5-content-safety:free |
| nvidia/nemotron-nano-12b-v2-vl:free |
| nvidia/nemotron-nano-9b-v2:free |
| apodex-1.1-mini:free |
| dots-3-note:free |
| lfm2.5-2.6b:free |
| thinkingmachines/inkling:free |
| thinkingmachines/inkling-small:free |

---

### Google AI Studio

**Endpoint:** `https://generativelanguage.googleapis.com/v1beta` (native) or via Vertex AI

**Limits:** Per-project dashboard values (approx. 20 req/day for Flash, 500 req/day for Flash-Lite, 5–15 req/min) · No card

**Note:** Data used for training outside UK/CH/EEA/EU.

**Free Models** (2026-10-10 dashboard):

| Model | Approx. Model Limits |
|---|---|
| Gemini 3.8 Flash | ~250,000 tok/min · ~20 req/day · 5 req/min |
| Gemini 3.6 Flash | ~250,000 tok/min · ~20 req/day · 5 req/min |
| Gemini 3 Flash Preview | ~250,000 tok/min · ~20 req/day · 5 req/min |
| Gemini 3.5 Flash-Lite | ~250,000 tok/min · ~500 req/day · 15 req/min |
| Gemini 3.1 Flash-Lite | ~250,000 tok/min · ~500 req/day · 15 req/min |
| Gemini 2.5 Flash | ~250,000 tok/min · ~20 req/day · 5 req/min |
| Gemini 2.5 Flash-Lite | ~250,000 tok/min · ~20 req/day · 10 req/min |
| Gemini 3.1 Flash TTS | ~10,000 tok/min · ~10 req/day · 3 req/min |
| Gemini 2.5 Flash TTS | ~10,000 tok/min · ~10 req/day · 3 req/min |
| Gemini Robotics-ER 1.6 | ~250,000 tok/min · ~20 req/day · 5 req/min |
| Gemini Robotics-ER 1.5 | ~250,000 tok/min · ~20 req/day · 10 req/min |
| Gemma 4 31B Instruct | ~16,000 tok/min · ~14,400 req/day · 30 req/min |
| Gemma 4 26B A4B Instruct | ~16,000 tok/min · ~14,400 req/day · 30 req/min |
| Gemma 3 27B Instruct | ~15,000 tok/min · ~14,400 req/day · 30 req/min |
| Gemma 3 12B Instruct | ~15,000 tok/min · ~14,400 req/day · 30 req/min |
| Gemma 3 4B Instruct | ~15,000 tok/min · ~14,400 req/day · 30 req/min |
| Gemma 3 1B Instruct | ~15,000 tok/min · ~14,400 req/day · 30 req/min |

---

### NVIDIA NIM

**Endpoint:** `https://integrate.api.nvidia.com/v1` (OpenAI-compatible)

**Limits:** 40 req/min · Phone verification required · No card

**Free Models:** [Various open models](https://build.nvidia.com/models) — context windows capped below max (e.g., ~131K for Nemotron-3-Nano).

---

### Mistral (La Plateforme)

**Endpoint:** `https://api.mistral.ai/v1` (OpenAI-compatible)

**Limits:** Per-model/per-org; only visible in [Admin Panel](https://admin.mistral.ai/plateforme/limits) · No public numbers · Phone verification required

**Note:** "Free mode" (formerly Experiment plan). Data training enabled by default — opt out in Admin → Privacy.

**Free Models:** [Open and proprietary Mistral models](https://docs.mistral.ai/getting-started/models/models_overview/)

---

### Vercel AI Gateway

**Endpoint:** `https://ai-gateway.vercel.sh/v1` (OpenAI-compatible) — routes to multiple providers

**Limits:** ~$5 free credit per 30 days · **Payment method required** (403 without) · [Pricing](https://vercel.com/docs/ai-gateway/pricing)

**Note:** Free tier covers subset of catalog with per-model rate limits.

---

### Kilo Gateway

**Endpoint:** `https://api.kilo.ai/api/gateway` (OpenAI-compatible + FIM)

**Limits:** 200 req/hr per IP, shared across free models ([rate limits](https://kilo.ai/docs/gateway/usage-and-billing#rate-limiting)) · No account needed

**Note:** Some free models (incl. NVIDIA endpoints) may log/train on prompts — check each model's policy.

**Free Models** (rotating; 2026-10-10):

- inclusionai/ling-3.1-flash
- stepfun/step-5-preview-free
- Cohere North Mini Code
- Kilo Auto Free (Router)
- OpenRouter Free Models (Router)
- NVIDIA Nemotron variants (incl. 3.5 Lightning)
- Poolside Laguna variants
- dots-3
- lfm-2.5
- inkling-small
- glyph-cluster
- lyria

---

### OpenCode Zen

**Endpoint:** `https://opencode.ai/zen/v1/chat/completions` (OpenAI + Anthropic Messages + Responses)

**Limits:** $0/token for free models · **Account + billing balance required** (anonymous/external blocked)

**Note:** Default zero-retention/no training; exceptions: Big Pickle, MiMo, Ling, Nemotron. Space Bunny, LongCat, Step 5 explicitly zero-retention. Models "available for a limited time."

**Free Models** (2026-10-10; rotating):

- Big Pickle (stealth)
- Space Bunny Free (stealth)
- LongCat 2.5 Preview Free
- Step 5 Preview Free
- Exo Free
- MiMo-V2.5 Free
- MiMo-V2.6-Flash Free
- MiMo V2 Flash Free
- MiMo V2 Omni Free
- MiMo V2 Pro Free
- Ling 3.1 Flash Free
- Ling 3.0 Flash Free
- Ling 2.6 Flash Free
- Ling 3.0 Flash Free
- Ling 3.0 Tiny Free
- Ling 3.0 Flash Fin Free
- Nemotron 3 Ultra Free
- Nemotron 3 Super Free
- Nemotron 3.5 Lightning Free
- Muse Spark 1.3 Contributor Free
- Muse Spark 1.2 Contributor Free
- North Mini Code Free
- Laguna S 2.1 Free
- Kimi K2.5 Free
- GLM-4.7 Free
- GLM-5 Free
- MiniMax M2.1 Free
- MiniMax M2.5 Free
- MiniMax M3 Free
- Qwen3.6 Plus Free
- Ring 2.6 1T Free
- Trinity Large Preview Free
- Hy3 Free
- Hy3 Preview Free
- DeepSeek V4 Flash Free
- Ox Alpha Free (Unlimited)
- Fledge Alpha Free
- Jev 1.13 Free

---

### Command Code

**Endpoint:** `https://api.commandcode.ai/provider/v1` (OpenAI + Anthropic compatible)

**Limits:** **API requires paid plan** — Go $1/mo (CLI only); GOAT $10/mo or Provider PAYG $15/mo for API. Free deal models cost $0 credits.

**Free Deal Models** (2026-10-10; "while capacity lasts"):

| Model | Limit |
|---|---|
| `laguna-s-2.1-free` | Free, no daily limit |
| `ling-3.1-flash:free` | Free, no daily limit |
| `ling-3.0-flash-sante:free` | 100 req/day |
| `glyph-cluster:free` | 100 req/day (stealth preview) |

---

### Z.ai

**Endpoint:** `https://api.z.ai/api/paas/v4/chat/completions` (OpenAI + Anthropic compatible; works with Claude Code/Cline)

**Limits:** Per-account unpublished · No card · Check [console](https://z.ai/manage-apikey/rate-limits)

**Free Models** (permanently $0 input/cached/output; verified 2026-10-10 [pricing](https://docs.z.ai/guides/overview/pricing)):

| Model | Type | Context |
|---|---|---|
| `glm-4.7-flash` | Text | 200K |
| `glm-4.5-flash` | Text | 128K |
| `glm-4.6v-flash` | Vision | 128K |

⚠️ **Naming trap:** GLM-5.3-Flash is **not free** (paid). Only 4.x Flash models above are $0. Z.ai does not commit to keeping them free indefinitely.

---

### AIHubMix

**Endpoint:** `https://aihubmix.com/v1/chat/completions` (OpenAI Chat + Anthropic Messages + Responses — all three protocols)

**Limits:** 10 trial calls (no expiry, no card). **$1 top-up** unlocks permanent: 100 req/day · 10 req/min · 1M tokens/day shared across free catalog ([free-models](https://aihubmix.com/models/free))

**Free Models** (60 rotating; 2026-10-10 highlights):

| Category | Models |
|---|---|
| **Coding** | `coding-glm-5.3-free`, `coding-glm-5.3-flash-free`, `coding-kimi-k3-free`, `coding-minimax-m3-free`, `kimi-for-coding-free`, `north-mini-code-free`, `laguna-s-2.1-free`, `laguna-xs-2.1-free` |
| **Xiaomi** | `xiaomi-mimo-v2.6-pro-free`, `xiaomi-mimo-v2.5-free`, `mimo-v2-flash-free` |
| **Google** | `gemini-3.8-flash-free`, `gemini-3.6-flash-free`, `gemini-3.5-flash-lite-free`, `gemma-4-31b-it-free` |
| **OpenAI** | `gpt-5.5-free`, `gpt-4.1-free`, `gpt-4.1-mini-free`, `gpt-4.1-nano-free`, `gpt-oss-20b-free` |
| **NVIDIA** | `nemotron-3-ultra-550b-a55b-free`, `nemotron-3.5-lightning-free`, `nemotron-3-super-120b-a12b-free` |
| **Others** | `ling-3.0-flash-free`, `hy3-free`, `qwen3.6-plus-preview-free`, `lfm-2.5-2.6b-free`, `dots-3-note-preview-free`, `glm-4.7-flash-free` |

---

### Requesty

**Endpoint:** `https://router.requesty.ai/v1` (OpenAI + Anthropic compatible; `ANTHROPIC_BASE_URL` supported)

**Limits:** 200 req/day on free models · No card, no trial timer · EU data residency · [Free models](https://www.requesty.ai/free-models)

**Note:** Full gateway on free tier: routing, fallback, caching, analytics.

**Free Models** (~13 rotating; check [model list](https://www.requesty.ai/models)):

- Nemotron 3 Ultra
- Laguna
- Gemma 4
- Ling 3.1
- Leanstral
- (and others — check live model list)

---

### Nous Portal

**Endpoint:** `https://portal.nousresearch.com/api/v1` (OpenAI-compatible)

**Limits:** Standard rate limits · **Keyless calls return 402** — mint a [Portal key](https://portal.nousresearch.com/api-docs) first

**Free Models** ($0.00/1M on [models page](https://portal.nousresearch.com/models), 2026-10-10):

- Ling 3.1 Flash
- Ling 3.0 Flash Fin
- Ling 3.0 Flash Sante
- LongCat 2.0
- LongCat 2.5 Preview
- Laguna S 2.1
- Laguna XS 2.1
- Step 3.7 Flash
- Step 5 Preview
- Solar Mini 4

---

### LLM7.io

**Endpoint:** `https://api.llm7.io/v1` (OpenAI-compatible)

**Limits:** 100K tokens/24hr · 1 req/s · 60 req/min · 250 req/hr · Free token from [dash.llm7.io](https://dash.llm7.io) · [Limits](https://docs.llm7.io/limits)

⚠️ Quotas **significantly reduced Oct 2026**; "may be reduced without notice" per terms. Anonymous tier exists but docs inconsistent — get a free token.

**Free Models:** `turbo`-tier only (check [Models API](https://docs.llm7.io/guides/models-api) for live list):

- GLM-5.3-Flash
- codestral-latest
- minimax-m2.7

---

### BazaarLink

**Endpoint:** `https://api.bazaarlink.ai/v1` (OpenAI + Anthropic Messages + Responses)

**Limits:** Server-owned free-model limits · No card · Free web search requires verified email · [llms.txt](https://bazaarlink.ai/llms.txt)

**Free Models:**

- `auto:free` router model
- Signup trial credits

---

### Groq

**Endpoint:** `https://api.groq.com/openai/v1` (OpenAI-compatible)

**Limits:** Per-model daily caps (1K req/day typical) · No card

**Note:** Llama 3.1 8B / 3.3 70B, groq/compound, Allam 2 7B, qwen3.6-27b removed from free tier Aug–Sep 2026.

**Free Models** (2026-10-10):

| Model | Limits |
|---|---|
| openai/gpt-oss-120b | 1,000 req/day · 8,000 tok/min |
| openai/gpt-oss-20b | 1,000 req/day · 8,000 tok/min |
| openai/gpt-oss-safeguard-20b | 1,000 req/day · 8,000 tok/min |
| qwen/qwen3.8-27b | 1,000 req/day · 8,000 tok/min |
| Whisper Large v3 | 2,000 req/day · 20 req/min |
| Whisper Large v3 Turbo | 2,000 req/day · 20 req/min |
| meta-llama/llama-prompt-guard-2-22m | 14,400 req/day |
| meta-llama/llama-prompt-guard-2-86m | 14,400 req/day |
| canopylabs/orpheus-arabic-saudi | 10 req/min · 100 req/day |
| canopylabs/orpheus-v1-english | 10 req/min · 100 req/day |

---

### Cohere

**Endpoint:** `https://api.cohere.ai/v1` (native) or via OpenAI-compatible proxy

**Limits:** 20 req/min · 1,000 req/month shared quota · No card · [Rate limits](https://docs.cohere.com/docs/rate-limits)

⚠️ **Terms caveat:** Trial keys are evaluation-only. Terms prohibit personal/family/household use; trial data may be used for R&D.

**Free Models:**

- c4ai-aya-expanse-32b
- c4ai-aya-vision-32b
- command-a-03-2025
- command-a-plus-05-2026
- command-a-reasoning-08-2025
- command-a-translate-08-2025
- command-a-vision-07-2025
- command-r-08-2024
- command-r-plus-08-2024
- command-r7b-12-2024
- Cohere North Mini Code

---

### Cloudflare Workers AI

**Endpoint:** `https://api.cloudflare.com/client/v4/accounts/{account_id}/ai/run/{model}` (native)

**Limits:** 10,000 neurons/day on Workers Free plan (resets 00:00 UTC) · [Pricing](https://developers.cloudflare.com/workers-ai/platform/pricing/#free-allocation) · No card

⚠️ **Paid-plan models:** `@cf/moonshotai/kimi-k2.6`, `@cf/moonshotai/kimi-k2.7-code`, `@cf/zai-org/glm-5.2` require Workers Paid plan or prepaid AI Gateway credits.

**Free Models** (2026-10-10):

- @cf/aisingapore/gemma-sea-lion-v4-27b-it
- @cf/google/gemma-4-26b-a4b-it
- @cf/ibm-granite/granite-4.0-h-micro
- @cf/nvidia/nemotron-3-120b-a12b
- @cf/openai/gpt-oss-120b
- @cf/openai/gpt-oss-20b
- @cf/qwen/qwen3-30b-a3b-fp8
- @cf/qwen/qwen3.8-27b
- @cf/zai-org/glm-4.7-flash
- @cf/zai-org/glm-5.3-flash
- @cf/moonshotai/kimi-k2.5
- DeepSeek R1 Distill Qwen 32B
- Gemma 2B Instruct (LoRA)
- Gemma 7B Instruct (LoRA)
- Llama 2 7B Chat (LoRA)
- Llama 3.1 8B Instruct (FP8)
- Llama 3.2 11B Vision Instruct
- Llama 3.2 1B Instruct
- Llama 3.2 3B Instruct
- Llama 3.3 70B Instruct (FP8)
- Llama 4 Scout Instruct
- Llama Guard 3 8B
- Mistral 7B Instruct v0.2 (LoRA)
- Mistral Small 3.1 24B Instruct
- Qwen 2.5 Coder 32B Instruct
- Qwen QwQ 32B

---

## Part Two — Providers with Trial Credits

> One-time or signup credit balance — not an ongoing free tier.

| Provider | Credits | Card Required | Models |
|---|---|---|---|
| [Fireworks](https://fireworks.ai/) | $1 | No (after spent) | [Various open](https://fireworks.ai/models) |
| [Baseten](https://app.baseten.co/) | ~$30 | No to start | [Any supported](https://www.baseten.co/library/) — pay by compute |
| [Nebius](https://tokenfactory.nebius.com/) | $1 (30-day expiry) | **Yes** | [Various open](https://tokenfactory.nebius.com/models) |
| [Novita](https://novita.ai/) | $1 voucher | No | [Various open](https://novita.ai/models) |
| [Upstage](https://console.upstage.ai/) | $10 | No | Solar Pro 4 / Solar Mini 4 |
| [NLP Cloud](https://nlpcloud.com/home) | $15 | No to claim | Various open |
| [Alibaba Cloud Model Studio](https://www.alibabacloud.com/en/product/modelstudio) | 1M tokens/model, 90 days (SG) | No | Qwen models — [enable Free Quota Only](https://www.alibabacloud.com/help/en/model-studio/new-free-quota) |
| [Modal](https://modal.com/) | $30/mo compute | Payment method on file | Compute only — LLM tokens billed separately since Sep 2026 |
| [Scaleway Generative APIs](https://console.scaleway.com/generative-api/models) | 1M tokens + 60 min audio | Payment method for base limits | gpt-oss-120b, glm-5.2, deepseek-v4-flash, qwen3.8-27b, gemma, mistral, Whisper |
| [Cerebras](https://cloud.cerebras.ai/) | $5 (30-day expiry) | **Yes (verified)** | gpt-oss-120b, qwen-3.8-27b · 5 RPM · 1M tokens/day |

---

## Removed / No Longer Free

Providers previously listed whose free access has ended (verified 2026-10-10).

| Provider | Status |
|---|---|
| **HuggingFace Inference Providers** | Monthly free credit removed — Free users now $0; $2/mo PRO-only |
| **Cerebras** | Permanently free tier retired 2026-07-16 — now $5/30-day trial w/ verified card |
| **AI21** | Studio + Jamba API sunset 2026-08-09 — now BYOK gateway |
| **Hyperbolic** | Serverless API retired — keys fail; credits only for GPU rentals |
| **SambaNova Cloud** | Free credit removed 2026-08-14 — card required; `402 PAYMENT_METHOD_REQUIRED` |
| **Inference.net** | Advertised credits not found on official pages; pivoted to observability |
| **GitHub Models** | Service retired 2026-07-30 (playground, catalog, API gone) |
| **Together AI** | No free tier — $5 minimum purchase required |

---

## Contributing

PRs welcome! Please:

1. **Verify claims** against the provider's official pricing/docs pages (not blog posts or third-party aggregators).
2. **One provider per PR** — link to the exact page showing the free tier/model.
3. **Follow the entry format** used in Part One: Endpoint, Limits, Note (if any), Free Models table/list.
4. **Date your verification** — add "Verified 2026-10-10" (or current date) in the entry.
5. **Update the Quick Comparison table** if adding a new provider.

See [CONTRIBUTING.md](CONTRIBUTING.md) for full guidelines.

---

## License

This directory is licensed under [CC-BY-4.0](LICENSE) — you may share and adapt with attribution.

---

## Changelog

- **2026-10-11** — Professional restructure: badges, quick-compare table, standardized entries, unified date format, contributing/license sections.
- **2026-10-10** — Added Z.ai, AIHubMix, Requesty, Nous Portal, LLM7.io, BazaarLink; expanded OpenCode Zen; added Command Code.
- **2026-10-10** — Full verification pass: 26 providers checked, 6 accurate, 13 corrected, 6 removed.
- **2026-10-10** — Initial directory from Lakeer.AI source docx.

---

*Last verified: 2026-10-10 · Rate limits and models change frequently — always recheck before production use.*