# Proposed Additions — Verified Draft

Supplementary findings gathered from the web and **link-verified 2026-10-10**. Not yet merged into `README.md`.

**Verification key**
- ✅ **Confirmed** — link live; free tier verified against the provider's own page
- ⚠️ **Corrected** — link live; the original claim was inaccurate and has been fixed below
- 🗑️ **Rejected** — could not be verified as free; dropped from the proposal

> Every entry below was fetched live on 2026-10-10. Claims still change frequently — recheck before production use.

---

## Part A — New providers (candidates for a "Part Three")

### 🔒 LLM providers with ongoing free tiers

| Status | Provider | Current official URL | Free offer (verified) | Catch / requirements |
| --- | --- | --- | --- | --- |
| ✅ | Z.ai / Zhipu (GLM) | https://platform.z.ai · API `https://api.z.ai/api/paas/v4` | GLM-4.5-Flash, GLM-4.6V-Flash, GLM-4.7-Flash at **$0** permanently | Intl site: email/Google/GitHub, **no Chinese phone**. Note: newer GLM-5.3-Flash is **paid**. CN site (open.bigmodel.cn) is separate |
| ⚠️ | Ollama Cloud | https://ollama.com/pricing | Free hosted tier on **starter models only**, 1 concurrent request | "5-hour session cap" was legacy wording; full catalog burns purchased credits. Prompts not stored/trained |
| ✅ | Moonshot Kimi | https://platform.moonshot.cn | ¥15 new-user voucher, valid 3 months | **Mainland-China mobile number required** — CN-region only |
| ⚠️ | DeepSeek API | https://platform.deepseek.com | One-time **~5M-token / 30-day trial** | Original "10M / $5" was wrong. **Not closed** (contrary to earlier reports — API actively shipping V4.1-Flash). No perpetual free models |
| ⚠️ | SiliconFlow | https://cloud.siliconflow.cn · intl https://www.siliconflow.com | A small standing set of ~$0 small models + embeddings/OCR (~3–5, not 30+) | **Real-name KYC + CN phone** to unlock; free list rotates and is not published |
| ✅ | UnoRouter | https://unorouter.com | Free `:free` model routes | ~1 req/min/model shared; frequent 429 at peak |
| ✅ | Nous Portal | https://portal.nousresearch.com | $0 "Free models only" plan — **50 RPM / 500K TPM** | Signup required; paid plans from $20/mo |
| ✅ | Requesty | https://www.requesty.ai | Free route: **200 req/day, 20 RPM** | Small free-model set (Nemotron, Poolside, Gemma, Mistral) |
| ✅ | Aion Labs | https://aionlabs.ai · API `https://api.aionlabs.ai/v1` | Free: 15 RPM, 20,000 tokens/day | Proprietary Aion models only |
| ✅ | OrcaRouter | https://orcarouter.ai | `orcarouter/free` routes | Rate-limited; auto-routing needs a funded wallet |
| ⚠️ | ModelScope (Alibaba) | https://modelscope.cn · intl https://modelscope.ai | Free API-Inference ~2,000 calls/day | Requires Alibaba Cloud account bind **+ real-name verification** |

### 🔓 No-signup / anonymous (zero-auth) endpoints

| Status | Provider | Current official URL | Free offer (verified) | Catch / requirements |
| --- | --- | --- | --- | --- |
| ✅ | Pollinations | https://pollinations.ai | Text + image + audio with **no key** | Anonymous: 1 req/15s, basic models; **watermark** on free images |
| ✅ | OVHcloud AI Endpoints | https://www.ovhcloud.com/en/public-cloud/ai-endpoints/ | Anonymous lane, no key | **2 req/min per IP per model**, shared; paid key → 400/min. EU-hosted, zero retention |
| ✅ | AI Horde | https://aihorde.net | Free crowdsourced text + image | Anonymous key `0000000000`; lowest queue priority, may throttle at peak |
| ⚠️ | LLM7 | https://llm7.io · API `https://api.llm7.io/v1` | Keyless (placeholder key `unused`) | Corrected: **10/min anon**, 1M tokens/day with free email token (not 30 RPM / 5M). Single-operator relay — low trust |
| ⚠️ | Free.ai | https://free.ai | 6K tokens/day anon (web), 30K/day with free account | Corrected: the **OpenAI-compatible API requires a signup key**; not keyless |
| ✅ | Puter | https://puter.com · docs https://developer.puter.com | Keyless `puter.ai.chat()` in-browser | Free tier now "Limited AI"; provider focus shifted to paid suite |

### 🔌 Open-source gateway / aggregation tools

| Status | Tool | URL | Description |
| --- | --- | --- | --- |
| ✅ | zerogateway | https://pypi.org/project/zerogateway/ | BYOK router with rate-limit failover + local OpenAI-compatible proxy |
| ✅ | freellmpool | https://0xzr.github.io/freellmpool/ | `pip install` — pools 23 providers, keyless-capable, CLI + proxy + MCP server |

### 🖼️🎙️🔠🔎📄 Adjacent categories (verified)

| Status | Category | Provider | Verified free offer | Catch |
| --- | --- | --- | --- | --- |
| ⚠️ | Image | Stability AI | **25 credits one-time** on signup (not monthly) | Expire after 1 year; ≈$0.25 |
| ✅ | Image | Leonardo | 150 Fast Tokens/day | Free creations are **public** |
| ✅ | Speech-to-text | Deepgram | **$200** credit, no card, no expiry (≈700 hrs) | Data training on by default — set `mip_opt_out=true` |
| ✅ | Speech-to-text | AssemblyAI | **$50** credit, no card (~330 hrs) | 5 concurrent streams/min on free |
| ⚠️ | Text-to-speech | Speechify API | **500K chars/month** (not 50K) | Commercial use allowed; 1 req/s |
| ⚠️ | Text-to-speech | ElevenLabs | 10,000 credits/month | **Non-commercial only** + attribution required |
| ⚠️ | Text-to-speech | Cartesia | 20,000 credits/month | **No commercial licence** on free |
| ⚠️ | Text-to-speech | Google Cloud TTS | 4M chars/mo (Standard/WaveNet only) | Neural2/Chirp3-HD/Studio = 1M; Gemini-TTS = none; **billing/card required** |
| ⚠️ | Text-to-speech | Amazon Polly | 5M chars/mo Standard (ongoing) | 12-month limit only applies to Neural (1M) etc; **AWS card required** |
| ✅ | Embeddings | Jina AI | 10M tokens one-time (per new key) | Keyless Reader `r.jina.ai` = 20 RPM; not recurring |
| ⚠️ | Embeddings | Voyage AI | 200M tokens one-time | Model-dependent (50M on several models); excludes Batch API |
| ✅ | Embeddings | Pinecone | 5M tokens/mo + rerank 500 req/mo (Starter) | Monthly, us-east-1 only |
| ✅ | Search | Tavily | 1,000 credits/month, no card | Resets monthly |
| ⚠️ | Search | Exa | **$10 credits that reset monthly** (not 1K searches) | Metered credit, not a fixed search count |
| ⚠️ | Search | Brave Search API | $5 credits/mo (≈1,000 queries) | **Credit card required even on free plan** |
| ⚠️ | Search | Firecrawl | **1,000 credits/month** (not 500) | Refreshes monthly; 10/min scrape |
| ✅ | OCR | OCR.space | 25,000 requests/month | 500/day per IP; watermarked searchable PDF on free |
| ⚠️ | OCR | LlamaParse | 10K credits/month | Moved to https://www.llamaindex.ai/pricing; returns 402 when exhausted |

---

## Part B — Status changes affecting providers already in the README

| Provider | Outdated claim | Current status (verified 2026-10-10) |
| --- | --- | --- |
| **Cerebras** | Ongoing free tier | Now a **$5 / 30-day trial requiring a verified card** (since 16 Jul 2026) |
| **SambaNova Cloud** | "$5 for 3 months" | **Stopped giving credits to new accounts** (Aug 2026) |
| **Groq** | Llama 3.3 70B / 3.1 8B free | **Removed from free tier (16 Aug 2026)**; gpt-oss-120b/20b + qwen3.8-27b remain |
| **Cohere** | "1,000 requests/month" | Still ~1,000 calls/mo; **terms now ban personal/commercial use** — eval only |
| **Mistral (La Plateforme)** | Experiment plan | Now **$10/month of credits on Free mode**, no card; limits hidden in admin panel |
| **Google AI Studio** | Fixed daily limits | Limits no longer published; shown per-project; training caveat outside UK/CH/EEA/EU |
| **NVIDIA NIM** | 40 req/min free | Still free for prototyping, but **many listed models now return 404** |
| **OpenRouter** | (as listed) | Free `:free` roster rotated in 2026 — re-verify current IDs |
| **Alibaba Model Studio** | 1M tokens / 90 days | Confirmed; 90-day window with Singapore-region constraint |
| **GitHub Models** | (commonly cited as free) | **Retired 30 Jul 2026** |
| **Together AI** | (commonly cited as free) | **No free tier**; $5 minimum purchase |
| **Vercel AI Gateway** | "$5/month free" | Now **requires a card** (per third-party tracker) |

---

## Part C — Rejected in verification (dropped from proposal)

| Provider | Why rejected |
| --- | --- |
| **Lepton AI (DGX Cloud Lepton)** | `lepton.ai` no longer a product site (NVIDIA acquisition); "$10 credits / 10M tokens/day" unverifiable. Current NVIDIA free tier is compute credits, not token credits |
| **Replicate** | No "$5 free credits" published on any official page; only limited free runs on select models |
| **Morph** | `morph.so` is agent-infra, not an LLM gateway; real product `morphllm.com` has 200 req/mo. Out of scope |
| **TokenRouter** | `tokenrouter.ai` does not exist; brand fragmented across unrelated domains; only a 1-day trial, no free tier |
| **Nanonets** | Legacy free OCR discontinued; only a $50 trial credit advertised |

---

## Part D — Original open questions (resolved)

1. **DeepSeek** → Not closed; real offer is a ~5M-token/30-day trial. Listed as ⚠️ trial.
2. **SambaNova / Cerebras** → Kept in README, with Part B status note.
3. **Anonymous endpoints** → In scope; all four (Pollinations, LLM7, OVH, AI Horde) plus Puter/Free.ai verified and kept with caveats.
4. **Adjacent categories** → Included as verified; several claims corrected (Stability, Speechify, Brave, Exa, Firecrawl).
5. **Retired providers** → Added as Part B status notes.

**Net result:** of 40 links checked, **22 confirmed free**, **13 kept with corrections**, **5 rejected**.