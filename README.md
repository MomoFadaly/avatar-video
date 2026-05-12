# avatar-video

> Create AI avatar videos with precise control over avatars, voices, scripts, scenes, and backgrounds using the HeyGen v2 API.

**Free. Apache 2.0. Bring-your-own-Claude.**

## What this is

A Claude skill bundle — a sanitized, attributed, downloadable subject-matter expert that runs inside Claude Code, Claude Desktop, or any Claude-API workflow. Drop it in, invoke it, get answers grounded in real practitioner content rather than generic LLM consensus.

Use when choosing a specific avatar and voice, writing exact scripts for a talking-head video, or composing multi-scene videos with backgrounds.

## Install

```bash
# Claude Code plugin install (one-line)
claude plugin install avatar-video --from https://fadaly.net/downloads/skills/avatar-video.zip
```

Or clone this repo into your local Claude skills directory (typically `~/.claude/skills/` on macOS / Linux):

```bash
git clone https://github.com/MomoFadaly/avatar-video.git
```

Or download the zip from [fadaly.net/skills/avatar-video](https://fadaly.net/skills/avatar-video) (the per-skill landing page on fadaly.net) and extract into `~/.claude/skills/`.

## What's in the bundle

| File | Size |
|---|---|
| `references/assets.md` | 9KB |
| `references/avatars.md` | 15KB |
| `references/backgrounds.md` | 7KB |
| `references/captions.md` | 6KB |
| `references/dimensions.md` | 7KB |
| `references/photo-avatars.md` | 24KB |
| `references/quota.md` | 5KB |
| `references/remotion-integration.md` | 18KB |
| `references/scripts.md` | 10KB |
| `references/templates.md` | 10KB |
| `references/text-overlays.md` | 7KB |
| `references/video-generation.md` | 22KB |
| `references/video-status.md` | 13KB |
| `references/voices.md` | 12KB |
| `references/webhooks.md` | 9KB |
| `SKILL.md` | 6KB |
| `thumb.png` | 785KB |

Total: 962KB

## Sources

This SME's canon was built from these practitioners. Every claim in the canon is attributed.

- HeyGen API v2 (docs.heygen.com)

Primary sources (official documentation, peer-reviewed research) take priority over practitioner consensus, which takes priority over single-source claims. Confidence tiers are tagged inline.

## How it works

Claude reads `SKILL.md` as the system instructions for the skill. Supporting files (`canon.md`, `mental-models.md`, etc.) are loaded as reference material when the skill needs to answer off the cuff or cite a specific source.

When you ask a question this SME covers, Claude pulls the relevant canon entry, names its source, tags its confidence level, and pushes back if your question contradicts canon.

## Confidence levels

- **Verified** — primary source + practitioner corroboration. Treat as fact.
- **Confirmed** — practitioner consensus across credible voices, no primary contradiction. Defended best-practice.
- **Plausible** — single-source or thin evidence. Working hypothesis until validated.
- **Disputed** — credible voices disagree. The SME names the camps and gives you the lens to decide.
- **Stale** — once true, contradicted by current docs/data. Flagged for refresh.

## License

Apache License 2.0. See [LICENSE](LICENSE).

You are free to use, modify, redistribute, and build on this skill. Attribution to the original practitioners (named in `sources.md` or `SKILL.md`) is morally required even if not legally; their work made the canon possible.

## More like this

This is one of a series of Claude skills published openly. See the [full catalog at fadaly.net/work](https://fadaly.net/work).
