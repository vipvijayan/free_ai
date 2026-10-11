# Free LLM API — Resource Directory

A curated, professionally organized reference of free and trial-credit LLM inference APIs — with verified, clickable links.

---

## About This Directory

This directory catalogues services offering free or trial-credit access to API-based LLM (Large Language Model) inference. Every provider name is a clickable hyperlink to its official console or homepage, and every documentation reference — rate limits, pricing, model catalogues — links directly to the primary source.

> **USAGE NOTE** — Please use these free services responsibly. Excessive or automated abuse risks providers withdrawing free access for the wider community.
>
> **SCOPE** — This directory excludes any service that is not a legitimate, officially sanctioned API (e.g. reverse-engineered or unofficial wrappers around an existing chatbot).

> **VERIFICATION** — All links and free-tier claims were re-verified against official provider pages on **10 October 2026**. Providers that have since retired their free access are listed in [Removed / No Longer Free](#removed--no-longer-free). Rate limits and model catalogues churn frequently — always recheck before relying on a tier.

---

## Contents

- [Part One — Free Providers](#part-one--free-providers)
  - [OpenRouter](#-openrouter)
  - [Google AI Studio](#-google-ai-studio)
  - [NVIDIA NIM](#-nvidia-nim)
  - [Mistral (La Plateforme)](#-mistral-la-plateforme)
  - [Vercel AI Gateway](#-vercel-ai-gateway)
  - [Kilo Gateway](#-kilo-gateway)
  - [OpenCode Zen](#-opencode-zen)
  - [Command Code](#-command-code)
  - [Z.ai](#-zai)
  - [AIHubMix](#-aihubmix)
  - [Requesty](#-requesty)
  - [Nous Portal](#-nous-portal)
  - [LLM7.io](#-llm7io)
  - [BazaarLink](#-bazaarlink)
  - [Groq](#-groq)
  - [Cohere](#-cohere)
  - [Cloudflare Workers AI](#-cloudflare-workers-ai)
- [Part Two — Providers with Trial Credits](#part-two--providers-with-trial-credits)
  - [Fireworks](#-fireworks)
  - [Baseten](#-baseten)
  - [Nebius](#-nebius)
  - [Novita](#-novita)
  - [Upstage](#-upstage)
  - [NLP Cloud](#-nlp-cloud)
  - [Alibaba Cloud (International) Model Studio](#-alibaba-cloud-international-model-studio)
  - [Modal](#-modal)
  - [Scaleway Generative APIs](#-scaleway-generative-apis)
  - [Cerebras](#-cerebras)
- [Removed / No Longer Free](#removed--no-longer-free)
- [Closing Notes](#closing-notes)

---

# Part One — Free Providers

> Ongoing free tiers — not one-time trial credits. No credit card required to start, except where noted.

## ▍ [OpenRouter](https://openrouter.ai/)

Models share a common quota.

**Limits** — 20 requests/minute · 50 requests/day · up to 1,000 requests/day with a $10 lifetime top-up ([limits docs](https://openrouter.ai/docs/api/reference/limits)) · No credit card

**Free Models** (as of Oct 2026 — the roster rotates; check the model page before relying on one)

| Model |
| --- |
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

## ▍ [Google AI Studio](https://aistudio.google.com/)

> Data is used for training when used outside of the UK / CH / EEA / EU. Rate limits are now shown per-project inside AI Studio rather than published; figures below reflect October 2026 dashboard values.

| Model Name | Approx. Model Limits |
| --- | --- |
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

## ▍ [NVIDIA NIM](https://build.nvidia.com/explore/discover)

> Phone number verification required. Free-tier context windows are capped below the models' full maximum (e.g. ~131K for Nemotron-3-Nano). SMS verification can be flaky in some regions.

**Limits** — 40 requests/minute

**Models** — [Various open models](https://build.nvidia.com/models)

---

## ▍ [Mistral (La Plateforme)](https://console.mistral.ai/)

> Free tier is now called **"Free mode"** (previously the Experiment plan). Data training is enabled by default in Free mode — opt out in Admin → Privacy. Requires phone number verification.

**Limits** — Per-model and per-organization; shown only in your [Admin Panel → API → Limits](https://admin.mistral.ai/plateforme/limits) (login required). Mistral no longer publishes numeric throughput publicly.

**Models** — [Open and Proprietary Mistral models](https://docs.mistral.ai/getting-started/models/models_overview/)

---

## ▍ [Vercel AI Gateway](https://vercel.com/docs/ai-gateway)

> Routes to various supported providers. The free tier covers a subset of the model catalogue, with per-model rate limits.

**Limits** — ~$5 of free credit per 30 days · **A valid payment method must be on file before free credits work** (returns `403 customer_verification_required` otherwise) — see [pricing](https://vercel.com/docs/ai-gateway/pricing)

---

## ▍ [Kilo Gateway](https://kilo.ai/docs/gateway)

> OpenAI-compatible gateway routing to various providers. Free models work without an account (verified anonymously). *Some* free models (including NVIDIA endpoints) log or train on prompts — check each model's policy.

**Limits** — 200 requests/hour per IP, shared across all free models ([rate limiting docs](https://kilo.ai/docs/gateway/usage-and-billing#rate-limiting))

**Free Models** (as of Oct 2026; rotates)

- inclusionai/ling-3.1-flash
- stepfun/step-5-preview-free
- Cohere North Mini Code
- Kilo Auto Free (Router)
- OpenRouter Free Models (Router)
- NVIDIA Nemotron variants (incl. 3.5 Lightning)
- Poolside Laguna variants
- dots-3, lfm-2.5, inkling-small, glyph-cluster, lyria

---

## ▍ [OpenCode Zen](https://opencode.ai/zen)

> AI gateway with curated, benchmarked models for coding agents. **OpenAI-compatible** — base URL `https://opencode.ai/zen/v1/chat/completions`. Free models are **$0 input/output** and are available "for a limited time" while teams collect feedback. Can be used with any agent (setup requires signing in and adding a billing balance — anonymous/external calls to the free tier are blocked). Privacy: default zero-retention/no training, with named exceptions (Big Pickle, MiMo, Ling, Nemotron, etc.); Space Bunny, LongCat and Step 5 explicitly follow zero-retention policies.

**Free Models** (as of Oct 2026 — official docs + catalog; rotates)

- Big Pickle (stealth) · Space Bunny Free (stealth) · LongCat 2.5 Preview Free · Step 5 Preview Free
- Exo Free · MiMo-V2.5 Free · MiMo-V2.6-Flash Free · MiMo V2 Flash / Omni / Pro Free
- Ling 3.1 Flash Free · Ling 3.0 Flash Fin Free · Ling 2.6 Flash Free · Ling-3.0-flash Free · Ling-3.0-tiny Free
- Nemotron 3 Ultra Free · Nemotron 3 Super Free · Nemotron 3.5 Lightning Free
- Muse Spark 1.3 Contributor Free · Muse Spark 1.2 Contributor Free
- North Mini Code Free · Laguna S 2.1 Free · Kimi K2.5 Free
- GLM-4.7 Free · GLM-5 Free · MiniMax M2.1 / M2.5 / M3 Free
- Qwen3.6 Plus Free · Ring 2.6 1T Free · Trinity Large Preview Free · Hy3 Free · Hy3 Preview Free
- DeepSeek V4 Flash Free · Ox Alpha Free (Unlimited) · Fledge Alpha Free · Jev 1.13 Free

---

## ▍ [Command Code](https://commandcode.ai/)

> Coding-agent platform (CLI + API) with an OpenAI- and Anthropic-compatible Provider API at `https://api.commandcode.ai/provider/v1`. Offers promotional **free deal models** ($0 in credits). ⚠️ **Requires a paid plan** — the $1/mo Go plan is CLI-only; **API access starts at the $10/mo GOAT plan** (or the $15/mo Provider PAYG plan). Free deal models do not draw down plan credits.

**Free Deal Models** (as of Oct 2026 — "while capacity lasts")

| Model | Limit |
| --- | --- |
| `laguna-s-2.1-free` | Free, no daily limit |
| `ling-3.1-flash:free` | Free, no daily limit |
| `ling-3.0-flash-sante:free` | 100 requests/day |
| `glyph-cluster:free` | 100 requests/day (stealth preview) |

---

## ▍ [Z.ai](https://z.ai/)

> Zhipu AI's public API — OpenAI-compatible at `https://api.z.ai/api/paas/v4/chat/completions` (plus an Anthropic-compatible endpoint; works with Claude Code and Cline). Three models are permanently priced at **$0 for input, cached input, and output** — genuine free models, not trial credits. No credit card. Rate limits are per-account and unpublished — check your own limits in the [console](https://z.ai/manage-apikey/rate-limits).

**Free Models** (verified against the [official pricing page](https://docs.z.ai/guides/overview/pricing), Oct 2026)

- `glm-4.7-flash` — text, 200K context (strongest of the three)
- `glm-4.5-flash` — text, 128K context
- `glm-4.6v-flash` — vision, 128K context

> ⚠️ **Naming trap** — the newer **GLM-5.3-Flash is NOT free** (it is a cheap paid model). Only the 4.x-generation Flash models above are $0. Z.ai does not commit to keeping them free indefinitely.

---

## ▍ [AIHubMix](https://aihubmix.com/models/free)

> Gateway subsidizing **60 models at $0 per million input & output tokens**. Every model answers all three protocols: OpenAI Chat Completions, Anthropic Messages, and Responses — works natively with Claude Code (`ANTHROPIC_BASE_URL`), Cursor, Cline, and LiteLLM. One key for all models.

**Limits** — No card: 10 trial calls to start (no expiry). A one-time **$1 top-up** permanently unlocks daily quotas: **100 requests/day · 10 requests/min · 1M tokens/day** shared across the free catalog ([free-models page](https://aihubmix.com/models/free))

**Free Models** (as of Oct 2026 — rotating; full list of 60 on the site)

- Coding: `coding-glm-5.3-free` · `coding-glm-5.3-flash-free` · `coding-kimi-k3-free` · `coding-minimax-m3-free` · `kimi-for-coding-free` · `north-mini-code-free` · `laguna-s-2.1-free` · `laguna-xs-2.1-free`
- Xiaomi: `xiaomi-mimo-v2.6-pro-free` · `xiaomi-mimo-v2.5-free` · `mimo-v2-flash-free`
- Google: `gemini-3.8-flash-free` · `gemini-3.6-flash-free` · `gemini-3.5-flash-lite-free` · `gemma-4-31b-it-free`
- OpenAI: `gpt-5.5-free` · `gpt-4.1-free` · `gpt-4.1-mini-free` · `gpt-4.1-nano-free` · `gpt-oss-20b-free`
- NVIDIA: `nemotron-3-ultra-550b-a55b-free` · `nemotron-3.5-lightning-free` · `nemotron-3-super-120b-a12b-free`
- Others: `ling-3.0-flash-free` · `hy3-free` · `qwen3.6-plus-preview-free` · `lfm-2.5-2.6b-free` · `dots-3-note-preview-free` · `glm-4.7-flash-free`

---

## ▍ [Requesty](https://www.requesty.ai/free-models)

> AI gateway with a free tier that is the full platform — routing, fallback, prompt caching, real-time analytics, and **EU data residency**. OpenAI-compatible at `https://router.requesty.ai/v1`; works in Claude Code (`ANTHROPIC_BASE_URL` = `https://router.requesty.ai`), Cline, Cursor, and Roo Code. No credit card, no trial timer.

**Limits** — 200 requests/day on free models ([free-models page](https://www.requesty.ai/free-models))

**Free Models** — marked in the live [model list](https://www.requesty.ai/models) (~13 rotating: Nemotron 3 Ultra, Laguna, Gemma 4, Ling 3.1, Leanstral, etc.)

---

## ▍ [Nous Portal](https://portal.nousresearch.com/)

> Nous Research's model gateway (powers Hermes Agent) with a **$0 Free plan**: free models only, standard rate limits, $0 monthly credits. OpenAI-compatible. Hundreds of models in the catalog, with $0.00/1M rows for the free ones. Keyless calls return HTTP 402 — you must mint a Portal key first ([API docs](https://portal.nousresearch.com/api-docs)).

**Free Models** ($0.00/1M listed on the [models page](https://portal.nousresearch.com/models), Oct 2026)

- Ling 3.1 Flash · Ling 3.0 Flash Fin · Ling 3.0 Flash Sante
- LongCat 2.0 · LongCat 2.5 Preview
- Laguna S 2.1 · Laguna XS 2.1
- Step 3.7 Flash · Step 5 Preview · Solar Mini 4

---

## ▍ [LLM7.io](https://llm7.io/)

> Small educational/research LLM gateway (OpenAI-compatible at `https://api.llm7.io/v1`). Free dashboard token from [dash.llm7.io](https://dash.llm7.io) — no credit card. Covers `turbo`-tier models only (e.g. GLM-5.3-Flash, codestral-latest, minimax-m2.7 — check the [Models API](https://docs.llm7.io/guides/models-api) for live tiers).

**Limits** (free token) — 100,000 tokens per 24 hours · 1 req/s · 60 req/min · 250 req/hr ([limits docs](https://docs.llm7.io/limits))

> ⚠️ Free quotas were **significantly reduced in Oct 2026** and "may be reduced without notice" per LLM7's own terms. An anonymous (keyless) tier also exists in the terms but current docs are inconsistent — get a free token to be safe.

---

## ▍ [BazaarLink](https://bazaarlink.ai/)

> OpenAI-compatible gateway at `https://api.bazaarlink.ai/v1` (also Anthropic Messages + Responses endpoints). No credit card on signup. Offers a zero-cost `auto:free` router model for free inference, plus signup trial credits ([llms.txt](https://bazaarlink.ai/llms.txt)).

**Limits** — Free-model rate and daily limits are server-owned; free web search requires a verified email

---

## ▍ [Groq](https://console.groq.com/)

> No credit card required. Llama 3.1 8B / Llama 3.3 70B, groq/compound, Allam 2 7B and qwen3.6-27b were decommissioned from the free tier in Aug–Sep 2026.

| Model Name | Model Limits |
| --- | --- |
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

## ▍ [Cohere](https://cohere.com/)

Models share a common monthly quota on a free trial key.

**Limits** — 20 requests/minute · 1,000 requests/month ([rate limits docs](https://docs.cohere.com/docs/rate-limits)) · No card

> ⚠️ **Terms caveat** — Cohere's trial keys are evaluation-only. Their Terms of Use prohibit personal, family, or household use, and trial data may be used for R&D. Read the terms before building on it.

**Models**

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

## ▍ [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai)

**Limits** — [10,000 neurons/day](https://developers.cloudflare.com/workers-ai/platform/pricing/#free-allocation) on the Workers Free plan, resetting 00:00 UTC

> ⚠️ **Paid-plan models** — `@cf/moonshotai/kimi-k2.6`, `@cf/moonshotai/kimi-k2.7-code` and `@cf/zai-org/glm-5.2` now require a Workers Paid plan or prepaid AI Gateway credits.

**Free Models** (as of Oct 2026)

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

# Part Two — Providers with Trial Credits

> One-time or signup credit balance — not an ongoing free tier.

| Provider | Credits | Card? | Models |
| --- | --- | --- | --- |
| [Fireworks](https://fireworks.ai/) | $1 | No to claim (needed after spent) | [Various open models](https://fireworks.ai/models) |
| [Baseten](https://app.baseten.co/) | ~$30 (reported; dashboard shows current balance) | No to start | [Any supported model](https://www.baseten.co/library/) — pay by compute time |
| [Nebius](https://tokenfactory.nebius.com/) | $1, **expires in 30 days** | **Yes — bank card required at onboarding** | [Various open models](https://tokenfactory.nebius.com/models) |
| [Novita](https://novita.ai/) | $1 credit voucher (per current FAQ) | No | [Various open models](https://novita.ai/models) |
| [Upstage](https://console.upstage.ai/) | $10 | No | Solar Pro 4 / Solar Mini 4 |
| [NLP Cloud](https://nlpcloud.com/home) | $15 | No to claim | Various open models |
| [Alibaba Cloud (International) Model Studio](https://www.alibabacloud.com/en/product/modelstudio) | 1M tokens per model, 90 days (Singapore endpoint) | No | Various open and proprietary Qwen models — [free-quota docs](https://www.alibabacloud.com/help/en/model-studio/new-free-quota); enable "Free Quota Only" to avoid auto-billing |
| [Modal](https://modal.com/) | $30/month included compute (recurring, not one-time) | Payment method on file | Compute only — **LLM Shared Endpoint tokens are billed separately since Sep 2026** |
| [Scaleway Generative APIs](https://console.scaleway.com/generative-api/models) | 1M free tokens + 60 min audio transcription | Payment method for base rate limits | Current models include gpt-oss-120b, glm-5.2, deepseek-v4-flash, qwen3.8-27b, gemma, mistral variants, Whisper |
| [Cerebras](https://cloud.cerebras.ai/) | $5 trial credit, **expires in 30 days** | **Yes — verified payment method required** | gpt-oss-120b, qwen-3.8-27b · 5 RPM · 1M tokens/day |

---

## Removed / No Longer Free

Providers previously listed in this directory whose free access has ended. Kept here so past references can be traced.

| Provider | Status (verified 10 Oct 2026) |
| --- | --- |
| **HuggingFace Inference Providers** | Monthly free credit removed — Free users now receive **$0.10 → none**; a $2.00/month credit is PRO-only |
| **Cerebras** | Permanently free tier **retired 16 Jul 2026** — now a $5/30-day trial requiring a verified card (moved to Part Two) |
| **AI21** | Studio + Jamba API **sunset 9 Aug 2026** — app.ai21.com is now a BYOK gateway, not hosted models |
| **Hyperbolic** | Serverless inference API **retired** — old keys fail; credits now only usable for GPU rentals |
| **SambaNova Cloud** | Free credit **removed 14 Aug 2026** — card now required; free accounts return `402 PAYMENT_METHOD_REQUIRED` |
| **Inference.net** | Advertised $1/$25-survey credit **not found on official pages**; site pivoted to an observability platform |
| **GitHub Models** | Service **retired 30 Jul 2026** (playground, catalog, API gone) |
| **Together AI** | No free tier — $5 minimum purchase required |

---

## Closing Notes

Rate limits, credit amounts, and model availability change frequently at each provider's sole discretion. Please verify current terms directly on each provider's website before relying on a free tier for production workloads. Links and free-tier claims in this directory were last verified on 10 October 2026 — see [README-VERIFICATION.md](README-VERIFICATION.md) for the full verification log.
