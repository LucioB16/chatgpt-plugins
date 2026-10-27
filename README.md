# Lyra & Iterloom · Plugin Information

**Two independent AI workflows, with public documentation and clear support policies.**

This repository hosts the lightweight information site for two skills-oriented ChatGPT plugins by **Lucio Bottacin**. It publishes their descriptions and the support, privacy and terms pages needed to evaluate them.

| Plugin | What it helps with | Learn more |
| :-- | :-- | :-- |
| **Lyra** | Transform rough requests into structured, model-aware prompts. | [Lyra](lyra/) |
| **Iterloom** | Review AI work sessions and extract evidence-based process improvements. | [Iterloom](iterloom/) |

**Public pages:** [Support](support/) · [Privacy policy](privacy/) · [Terms of service](terms/).

> [!NOTE]
> This is a **buildless information website**, not the plugin implementation or a hosted AI service. It uses static HTML and CSS only. The plugins do not operate a developer-hosted MCP backend from this site.

## GitHub Pages deployment

This is a buildless static site: HTML and CSS only, no JavaScript, no tracking, no contact-form backend, no dependencies.

To publish from this repository, go to **Settings → Pages**, choose **Deploy from a branch**, then select **main** and **/(root)**. The expected project site URL is:

`https://luciob16.github.io/chatgpt-plugins/`

### Plugin listing URLs

| Field | Lyra | Iterloom |
| --- | --- | --- |
| `websiteURL` | `https://luciob16.github.io/chatgpt-plugins/lyra/` | `https://luciob16.github.io/chatgpt-plugins/iterloom/` |
| `supportURL` | `https://luciob16.github.io/chatgpt-plugins/support/` | same |
| `privacyPolicyURL` | `https://luciob16.github.io/chatgpt-plugins/privacy/` | same |
| `termsOfServiceURL` | `https://luciob16.github.io/chatgpt-plugins/terms/` | same |

These URLs become live after GitHub Pages is enabled and deployment completes. Do not submit plugin package metadata pointing to these URLs before confirming they respond successfully.

## Publisher and support

Publisher: **Lucio Bottacin**. For support, open a public issue in [this repository](https://github.com/LucioB16/chatgpt-plugins/issues). Please do not include private conversation exports, account credentials, payment information, or other sensitive data in public issues.

The plugins currently contain no developer-operated MCP server or analytics backend. Host AI platform handling and GitHub Pages security logs are described in the privacy policy.

This site is independent and is not affiliated with or endorsed by OpenAI, Anthropic, Google, or GitHub.
