<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 041 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 041

### Build one source-earned metaphor into a luminous isometric study

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-EA846F?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-6FAEB4?style=flat-square)](#)

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<div>

> THEME METAPHOR · ISOMETRIC ORDER · PALE MANUSCRIPT · JAPANESE COLOUR · EASTERN SPACE

One coherent isometric model preserves the source while a single geometric metaphor becomes its base, gap, path, enclosure, or negative shape. Faint research sketches remain subordinate traces of thought around the luminous finished form.

## Why this Skill exists

The style is source-dependent, not a decorative preset. Its operative transformation is:

```text
lock identity and structural axes → preserve three defining cues → rebuild with one coherent isometric grid → derive one source-earned metaphor → make the metaphor govern base, cut, path, enclosure, support, or negative space → use luminous source-derived Japanese colour and matte planes → surround with faint analytic studies → align copy to axes and construction lines
```

If an unrelated photograph could replace the source without materially changing recognition, construction, placement, material, colour, whitespace, and copy, the result does not belong to this Panel.

## The visual contract

- Preserve at least three cues across silhouette, proportion, axis, opening, layer, direction, action, or relation.
- Use one coherent isometric axis system and rebuild meaningful masses, levels, cuts, and spatial relations; never merely turn the object into a generic 3D model.
- Derive one theme image from actual content, action, structure, or symbolism and make it causally control the base, cut, gap, path, enclosure, support, suspension, or negative form.
- Use high-value, clean, soft Japanese colour derived from the source, a pale warm foundation, matte surfaces, and light legible shading without plastic gloss or heavy CG.
- Add only faint source-related contour studies, decompositions, close-ups, proportion lines, arrows, geometric trials, natural observations, and micro-notes; they remain subordinate thinking traces.
- Use source-earned offset, suspension, scale contrast, cropping, and generous Eastern whitespace while maintaining one visual centre.

Complete aesthetic constraints and rejection rules live in the Skill and production prompts. They preserve the original brief without turning its historical 3:4 canvas into a hidden default. [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-041-prompt.en.md)

## Samples · From X

> [Xiaoxiaodong (@xiaoxiaodong01)](https://x.com/xiaoxiaodong01/status/2091001986519068891) · 22 August 2026<br>
> GPT2 × isometric × Leonardo da Vinci × aesthetic prompt<br>Note: “VOL.401” in the original post is a numbering typo; the author has confirmed these samples belong to XXD Panel 041.

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 041 sample 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 041 sample 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 041 sample 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 041 sample 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891">View the original post and full prompt →</a></p>

These samples demonstrate the 041 aesthetic motive. Their subjects, composition, palette, copy, and earlier canvas ratio never become generation references or current defaults.

## Four combinable output modes

Choose one or several modes with `1`, `1+3`, `1,2,4`, or `all`; `all` produces seven separate PNGs per source. After mode selection and before generation, the Skill explicitly asks for the whole finished canvas: the original-prompt `3:4`, an explicit source-aspect choice, a common ratio, or custom ratio/exact pixels. Source dimensions are never applied silently.

| Mode | Canvas rule | Result |
| --- | --- | --- |
| `top-bottom` | user-confirmed whole canvas | one complete generation: high-fidelity source above, 041 design below, approximately 50/50 |
| `left-right` | user-confirmed whole canvas | one complete generation: high-fidelity source left, 041 design right, approximately 50/50 |
| `design-only` | user-confirmed whole canvas | 041 design fills the canvas; source remains invisible |
| `wallpaper-pack` | confirmed per device | separate phone, iPad, desktop, and children's-watch PNGs |

Paired modes use the source as a high-fidelity edit/reference input and one complete style prompt to generate the finished composition directly, so photography, design, colour, light, typography, and meaning can cohere. Deterministic composition is fallback-only: after one targeted complete-canvas retry fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless final pixel calibration.

Wallpapers may be linked or independent. A linked pack approves one iPad anchor, then recomposes every other device from the original plus that same anchor. An independent pack gives each device only the original. Neither crops another device output nor chains derivatives.

## Copy and locale

Automatic copy, exact custom copy, or text-free output is confirmed before generation. Copy follows the intended audience rather than the command language, and exact user wording remains verbatim.

Project-specific copy rule: Use one concise source-bound title plus only necessary place, state, or micro-annotation. Align native text with isometric axes, metaphor boundaries, cut planes, or faint construction lines so it reads as an art-publication information layer.

## Complete-canvas first, raster-only delivery

The image model owns the aesthetics of the entire finished composition; paired layouts also default to one complete-canvas generation. `scripts/compose_panel.py` remains only for condition-based recovery, lossless pixel calibration, and read-only audit. It is not run pre-emptively and does not judge aesthetic success.

Every deliverable is a raster PNG and every invocation creates a fresh task under `~/Desktop/xxd/`. The configured image route exposes sanitised status only—never providers, endpoints, credentials, headers, prompts, responses, or account details. SVG, HTML, Canvas, diagrams, and programmatic drawing are not substitutes for the final artwork.

## Get started

```bash
git clone https://github.com/nevertoday/xxd-panel-041.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-041" ~/.codex/skills/xxd-panel-041
```

Claude Code users may link the same folder under `~/.claude/skills/xxd-panel-041`. Restart the agent session after installation.

```text
$xxd-panel-041
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

Full specifications: [Skill workflow](SKILL.md) · [source archive](references/041-source.md) · [English prompt](references/xxd-panel-041-prompt.en.md) · [Chinese prompt](references/xxd-panel-041-prompt.zh-CN.md)

## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. Created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Support and membership

### In-depth consultation · CNY 299/hour

One-to-one in-depth consultation for using Skills. Contact Xiaoxiaodong through WeChat. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills User Community · CNY 99

A one-time fee joins the Skills user community for workflow sharing and peer discussion; hourly consultation is separate.

### Knowledge Planet + Member Prompt Library · CNY 699/year

One annual payment opens both Knowledge Planet and the member prompt library. Join either side, then contact Xiaoxiaodong on WeChat for the other access.

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>The finished form and the trace of thought share one quiet field.</strong></div>

---

<div align="center">

## Support this open-source project

Chinese-language support may use Xiaoxiaodong's own WeChat or Alipay reward codes; other editions use Buy Me a Coffee. Support is optional and never changes access to the open-source project.


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
