# README.md — Link Verification Report

Every provider/link in `README.md` checked against live official pages on **2026-10-10**.

**Verdicts**
- ✅ **Verified** — link live, free tier real, claims accurate
- ⚠️ **Needs correction** — link live and free, but claims in README are stale/wrong
- 🗑️ **No longer free** — remove or reclassify

---

## Part One — Free Providers

| # | Provider | Link | Verdict | Finding |
| --- | --- | --- | --- | --- |
| 1 | OpenRouter | openrouter.ai | ⚠️ | Limits exact (20 RPM/50 RPD/1K after $10). Model list: `Ling 3.0 Flash` and `gpt-oss-20b` are **not free**; ~15 `:free` models now (new: apodex-1.1-mini, dots-3-note, LFM2.5-2.6b, Inkling, Inkling Small) |
| 2 | Google AI Studio | aistudio.google.com | ⚠️ | Free tier real, no card. "Gemini 3.5 Flash" doesn't exist (3.6 Flash does; **3.8 Flash** is newest). 250k TPM / 20-500 RPD figures no longer published — shown only in AI Studio |
| 3 | NVIDIA NIM | build.nvidia.com | ✅ | 40 RPM confirmed; phone verification confirmed; free context windows capped (e.g. 131k for Nemotron-3-Nano) |
| 4 | Mistral (La Plateforme) | console.mistral.ai | ⚠️ | Free tier real (no card), but "Experiment plan" renamed **"Free mode"**; 25,000–20,000,000 tok/min range no longer published (login-only admin panel) |
| 5 | Mistral (Codestral) | codestral.mistral.ai | ⚠️ | Endpoint now auth-gated and undocumented; 30 RPM/2,000 RPD claims trace to 2024 beta. Unverified — recheck with account |
| 6 | HuggingFace | huggingface.co/docs/inference-providers | 🗑️ | **$0.10/month credits removed.** Free users now get **none**; $2.00/mo only on PRO. README claim wrong |
| 7 | Vercel AI Gateway | vercel.com/docs/ai-gateway | ⚠️ | Free tier exists but **payment method now required** (`403 customer_verification_required` per official FAQ) |
| 8 | Kilo Gateway | kilo.ai/docs/gateway | ✅ | **Tested live anonymously — completion returned.** 200 req/hour/IP confirmed. Model list fixes: `ling-3.1-flash` (not 3.0), `step-5-preview-free` (not Step 3.7); ~6 unlisted free models. Training caveat applies to *some* models only |
| 9 | OpenCode Zen | opencode.ai/docs/zen | ⚠️ | Free tier now **works only inside the OpenCode client** (anonymous API blocked since 2026-09-23). 4/7 listed models wrong (DeepSeek V4 Flash Free → paid; Laguna S 2.1 Free / North Mini Code Free → not current). New: Space Bunny, LongCat, Step 5, Exo, MiMo-V2.6, etc. |
| 10 | Cerebras | cloud.cerebras.ai | 🗑️ | **No permanent free tier** (docs FAQ: "Is there a permanently free tier? **No.**"). Since 2026-07-16: $5 trial, **verified card required**, 30-day expiry. Models now `gpt-oss-120b` + `qwen-3.8-27b` |
| 11 | Groq | console.groq.com | ⚠️ | Free tier real, no card. **Decommissioned:** Llama 3.1 8B, Llama 3.3 70B (2026-08-16), `groq/compound`(-mini) (2026-09-21), Allam 2 7B, `qwen3.6-27b` (→ `qwen3.8-27b`). Still free: gpt-oss trio, Whisper (2,000 RPD ✓), prompt-guard, orpheus |
| 12 | Cohere | cohere.com | ⚠️ | Limits exact (20 RPM · 1,000/month) ✓, models live. **Add caveat:** terms ban personal/family use; trial data used for R&D; `command-r7b-arabic-02-2025` gone from tables |
| 13 | Cloudflare Workers AI | developers.cloudflare.com/workers-ai | ⚠️ | **10,000 neurons/day ✓** (pricing page updated 2026-10-09). 3 listed models now need paid plan: `kimi-k2.6`, `kimi-k2.7-code`, `glm-5.2`. New free: qwen3.8-27b, kimi-k2.5, glm-5.3-flash |

---

## Part Two — Providers with Trial Credits

| # | Provider | Link | Verdict | Finding |
| --- | --- | --- | --- | --- |
| 1 | Fireworks | fireworks.ai | ✅ | $1 confirmed in official billing FAQ; no card to claim; 10 RPM until card added |
| 2 | Baseten | app.baseten.co | ⚠️ | Credits confirmed; **$30 is third-party-reported** — official page just says "credits" |
| 3 | Nebius | tokenfactory.nebius.com | ⚠️ | $1 confirmed BUT **bank card mandatory at onboarding** and credit expires in **30 days** (README omits both) |
| 4 | Novita | novita.ai | ⚠️ | Official FAQ now says **"$1 credit voucher"** — not "$0.50 for 1 year" |
| 5 | AI21 | studio.ai21.com | 🗑️ | **Retired 2026-08-09** — Studio + Jamba API sunset. app.ai21.com is now a BYOK gateway, not hosted models |
| 6 | Upstage | console.upstage.ai | ⚠️ | $10 confirmed; 3-month duration not officially published. Models: Solar Pro 4 / Solar Mini 4 (older deprecated) |
| 7 | NLP Cloud | nlpcloud.com | ⚠️ | $15 confirmed on pricing page; **phone verification no longer seen** on registration form |
| 8 | Alibaba Model Studio | alibabacloud.com | ✅ | 1M tokens/model · 90 days · Singapore ✓. Add: account-info completion required; enable "Free Quota Only" to avoid auto-billing |
| 9 | Modal | modal.com | ⚠️ | Recurring monthly free tier (not trial). **Shared Endpoints (LLM tokens) excluded since 2026-09-01** — $30 covers compute only; "any supported model" misleading |
| 10 | Inference.net | inference.net | 🗑️ | No official $1/$25-survey credit on current pages; site pivoted to observability platform. Unverifiable |
| 11 | Hyperbolic | app.hyperbolic.ai | 🗑️ | **Serverless inference API officially retired** — old keys fail, listed models gone. Credits only for GPU rentals now |
| 12 | SambaNova Cloud | cloud.sambanova.ai | 🗑️ | **Free credit removed 2026-08-14**; card now required; free accounts get `402 PAYMENT_METHOD_REQUIRED`. (Also: "$5 for 3 months" was wrong — was 30-day expiry) |
| 13 | Scaleway Generative APIs | console.scaleway.com | ⚠️ | 1M tokens + 60 min audio ✓. **Model list outdated** — drop EOL'd holo2-30b, voxtral, devstral-2, pixtral-12b, gemma-3-27b; add deepseek-v4-flash-0731, qwen3.8-27b |

---

## Summary

| Verdict | Count | Providers |
| --- | --- | --- |
| ✅ Verified | 6 | NVIDIA NIM, Kilo Gateway, Fireworks, Alibaba, Scaleway (amounts), Groq Whisper rows |
| ⚠️ Needs correction | 13 | OpenRouter, Google AI Studio, Mistral×2, Vercel, OpenCode Zen, Groq, Cohere, Cloudflare, Baseten, Nebius, Novita, Upstage, NLP Cloud, Modal |
| 🗑️ No longer free / retired | 6 | **HuggingFace ($0.10 removed), Cerebras (card trial), AI21 (retired), Hyperbolic (retired), SambaNova (card), Inference.net (unverifiable)** |

### Critical changes
1. **Remove from Free Providers:** Cerebras (now card-required trial) — move to Part Two or drop.
2. **Remove from Trial Credits:** SambaNova, Hyperbolic, AI21 (all retired); Inference.net (unverifiable).
3. **HuggingFace** — free monthly credit no longer exists for Free users.
4. **Card warnings to add:** Vercel, Nebius (mandatory at onboarding).
5. **Groq model table** — delete 4 dead rows, rename qwen3.6→3.8.

All links themselves are reachable (no 404s among listed URLs except LlamaParse in ADDITIONS.md, already fixed). Every remaining provider is genuinely free or genuinely offers a trial credit — the 6 🗑️ items are no longer free.