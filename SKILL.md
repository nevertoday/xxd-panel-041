---
name: xxd-panel-041
description: "Create XXD Panel 041 artwork from supplied photos in four combinable modes: photo above/luminous Japanese-colour isometric editorial model embedded in a source-earned metaphor and surrounded by faint research sketches below, photo left/design right, design alone, or a four-device wallpaper pack with independent or anchor-linked continuity. Use for the exact 041 style; reject generic 3D model, game diorama, engineering axonometric drawing, low-poly cartoon, metaphor added as decoration, dominant manuscript clutter, heavy shadows, plastic material, mechanical centring, e-commerce display, template composition."
---

# XXD Panel 041 · 主题隐喻等距模型与研究手稿

Rebuild the source as one clear isometric editorial model whose blocks, cuts, levels, and spatial relations preserve identity. A single geometric metaphor becomes its base, gap, path, enclosure, or negative shape, while faint Leonardo-like studies reveal the thinking around the finished form.

Operational rules follow the shared XXD Panel workflow contract: four combinable modes; an explicitly confirmed whole-canvas ratio or exact resolution before generation; single complete-canvas raster generation by default; high-fidelity source reference in paired modes; linked or independent four-device wallpapers; copy and locale preflight; fresh generation jobs; privacy-preserving raster generation; deterministic composition as fallback only; and one fresh task directory per source and mode. Style-specific sections refine aesthetics and copy but never override this contract.

## Non-negotiable contract

- One source may use one or more selected modes. Each selected ordinary mode (`top-bottom`, `left-right`, `design-only`) produces one PNG; `wallpaper-pack` produces four separate PNGs. Selecting all four modes produces seven final files per source. Never combine them into a grid, contact sheet, overview, or mockup.
- Resolve a non-empty ordered set of modes. Accept one choice, multiple choices separated by `+`, Chinese/English commas or whitespace, natural-language names, or `全部` / `all`; deduplicate and execute in menu order 1→4.
- If `wallpaper-pack` is selected, resolve `linked` or `independent`. A linked pack approves one iPad anchor by default, then every other device references the original source plus that same anchor. An independent pack gives every device only the original. Never crop one wallpaper into another and never chain derivatives.
- Paired modes target a visually equal 50/50 relationship within one coherent generated canvas. Minor generative deviation is acceptable unless the user explicitly requires pixel-exact halves; exact deterministic geometry belongs to the documented fallback. `design-only` and every wallpaper show no source photo, seam, or reserved photographic panel.
- The whole final canvas ratio or exact pixels must be explicitly resolved before generation. Offer the archived/original-prompt 3:4, source aspect as an explicit choice, common ratios, or custom ratio/pixels; never infer explicitly selected final-canvas dimensions silently. Exact pixels take precedence over an explicitly chosen ratio.
- Keep visible photography faithful: restrained editorial grading and necessary environmental extension only; never stretch, distort, repaint, replace, or structurally alter the source.
- Preserve at least three source-specific identity, structure, pose, direction, action, function, opening, colour, distance, or relation cues in every transformed frame.
- Copy has no silent default. Before generation resolve `自动文案`, `自定义文案`, or `无文字`; automatic and custom modes also require target language or locale. Preserve exact user copy verbatim.
- Render no logo, watermark, signature, colour swatch, UI, device mockup, decorative pseudo-text, or unrelated prose.

## Aesthetic motive lock

Every transformed frame must visibly follow this source-bound chain:

**lock identity and structural axes → preserve three defining cues → rebuild with one coherent isometric grid → derive one source-earned metaphor → make the metaphor govern base, cut, path, enclosure, support, or negative space → use luminous source-derived Japanese colour and matte planes → surround with faint analytic studies → align copy to axes and construction lines**.

Reject the result as generic if an unrelated photograph could replace the source without materially changing recognition, construction, placement, material, colour relation, whitespace, or copy. The operative exclusions are: generic 3D model, game diorama, engineering axonometric drawing, low-poly cartoon, metaphor added as decoration, dominant manuscript clutter, heavy shadows, plastic material, mechanical centring, e-commerce display, template composition.

## 041 visual system

- Preserve at least three cues across silhouette, proportion, axis, opening, layer, direction, action, or relation.
- Use one coherent isometric axis system and rebuild meaningful masses, levels, cuts, and spatial relations; never merely turn the object into a generic 3D model.
- Derive one theme image from actual content, action, structure, or symbolism and make it causally control the base, cut, gap, path, enclosure, support, suspension, or negative form.
- Use high-value, clean, soft Japanese colour derived from the source, a pale warm foundation, matte surfaces, and light legible shading without plastic gloss or heavy CG.
- Add only faint source-related contour studies, decompositions, close-ups, proportion lines, arrows, geometric trials, natural observations, and micro-notes; they remain subordinate thinking traces.
- Use source-earned offset, suspension, scale contrast, cropping, and generous Eastern whitespace while maintaining one visual centre.

## Copy belongs to the image language

Use one concise source-bound title plus only necessary place, state, or micro-annotation. Align native text with isometric axes, metaphor boundaries, cut planes, or faint construction lines so it reads as an art-publication information layer.

Copy must pass the unrelated-image swap test. Preserve exact supplied wording verbatim; refine only an explicitly editable direction while protecting audience, purpose, mandatory words, tone, implication, and semantic line breaks.

Resolve locale independently from command language:

```text
target market or audience > requested output language > direction language; if none is explicit, ask before generation
```

Use native wording, rhetoric, punctuation, spacing, shaping, direction, and line breaks. Never infer nationality or audience language from appearance, clothing, scenery, filenames, metadata, or signs.

## Raster generation and privacy

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is exposed through the host's built-in image tool or an already configured compatible route, use it before any other model. Preserve the current XXD execution contract: resolve the whole final canvas before generation, use the source as a high-fidelity reference, generate paired modes as one complete canvas, and keep deterministic composition as fallback only.
- Also support **Seedance 5.0 Pro**, **Nano Banana Pro (Gemini Image Pro)**, **Nano Banana 2 (Gemini Image Flash)**, or another compatible bitmap model when it is actually available through a tool or configured route and can satisfy the selected mode. Required capabilities include reference-image generation/editing, source fidelity, the resolved whole-canvas ratio, native target-language text, and multi-image reference input when a linked wallpaper pack needs it.
- Alternative models are secondary routes, not a different workflow. Do not let a model switch silently change the selected modes, final canvas, source-visibility rules, copy, locale, wallpaper relationship, fresh-task boundary, raster-only delivery, or the full-canvas-first strategy. If an alternative cannot satisfy a hard requirement, do not silently degrade that requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. A user may voluntarily provide credentials for the current task. Accept them without echoing, displaying, logging, or reporting their value. Do not persist credentials or modify provider, account, billing, or global route configuration unless the user explicitly asks for that configuration change.
- Determine availability from an actual image-capability check. Do not declare GPT Image 2 or every other route unavailable merely because one tool is absent, one call failed, or one expected environment variable is unset.

Prefer GPT Image 2 through the host's built-in bitmap generation capability when exposed, and follow the available `imagegen` skill for the built-in execution details. Use one generation call per distinct asset; a wallpaper pack needs four. Style language describes raster appearance only and never authorises SVG, HTML, CSS, Canvas, 3D code, diagrams, or programmatic drawing as the artwork.

If built-in generation is unavailable, use the bundled privacy-safe configured route:

```bash
python3 scripts/configured_imagegen.py probe
python3 scripts/configured_imagegen.py edit --image source.png \
  --prompt-file /private/job-temp/transform-prompt.txt \
  --out /private/job-temp/design.png --size 1536x1024 --quality high
```

Judge readiness by actual bitmap capability, not a provider name or a single environment variable. Never display, echo, log, or report the user's actual provider, endpoint, headers, credential values, account identifiers, route configuration, prompts, responses, or secrets. Do not persist user-provided credentials or modify global route configuration unless explicitly requested. The bridge's sanitised status is the entire allowed diagnostic surface. An explicit invocation with source and desired output authorises any already configured authenticated bitmap route available to the session; do not request another confirmation solely because the route changes.

Only report generation unavailable after checking preferred GPT Image 2, every eligible exposed alternative, the bundled sanitised probe, and any suitable route or API key the user elects to provide. State the limitation narrowly, never guess its cause or expose the user's actual provider, and never substitute code-rendered art.

## Fresh-task and source boundary

Every invocation starts a fresh job unless the user explicitly asks to continue, audit, compare, edit, or reuse a named result. Repeating the same source and settings still requires fresh generation. An old file can never satisfy a new request.

Use only current attachments, explicit paths, or a previously supplied image clearly identified by the user. Never scan Desktop, `~/Desktop/xxd/xxd-panel-041/`, or historical task folders for a substitute.

## Workflow

1. Resolve one or more modes. If missing, ask exactly this as normal multiline chat text and wait:

   ```text
   请选择一个或多个模式（回复序号；多选可用 +、顿号或逗号）：

   1. 上下双联（原图在上＋041 设计在下）
   2. 左右双联（原图在左＋041 设计在右）
   3. 纯设计版（只显示 041 设计画面）
   4. 四端壁纸套装
      手机＋iPad＋电脑＋儿童手表

   示例：1｜1+3｜1、2、4｜全部
   ```

2. Before any ordinary-mode generation, explicitly resolve the **final finished canvas**, not the size of one panel. If the user did not already supply a ratio or exact pixels, ask and wait:

   ```text
   请选择最终成品画幅（回复序号即可；多选模式可共用，也可分别指定）：

   1. 原提示词画幅 3:4
   2. 跟随原图比例
   3. 常用比例
      1:1｜4:5｜2:3｜3:2｜16:9｜9:16
   4. 自定义比例或准确像素

   这里指整张最终成品的比例，不是单个区域。
   示例：1｜3：9:16｜4：2160×3840
   ```

   “跟随原图比例” is valid only when the user explicitly selects it. Never infer a silent canvas from the source dimensions, orientation, archived 3:4 brief, mode, or previous output. In multi-select, ask which mode an ambiguous ratio belongs to. Exact pixels take priority over a chosen ratio. For paired modes, odd split axes are allowed for direct generation; require an even split axis only if deterministic fallback composition is actually triggered.

3. Before generation, resolve copy mode and locale. If missing, ask and wait:

   ```text
   正式做图前，请确认文字设置（回复序号即可）：

   1. 自动文案
      我根据原图与 041 气质创作文案；请同时注明语言或地区
   2. 自定义文案
      请直接输入要呈现的准确文字，并注明语言或地区
   3. 无文字

   示例：1｜日语
   示例：2｜英式英语｜STILL IN BLOOM
   ```

   Automatic copy must be source-specific and native to the resolved locale. Preserve exact custom copy verbatim. Do not infer locale from appearance, clothing, scenery, filenames, metadata, or visible signs.

4. Only when `wallpaper-pack` is selected, resolve its relationship and device sizes. Ask for `1. 连贯套装` or `2. 四张独立` when missing. A linked set approves one iPad anchor by default; the other three outputs each reference the original plus that same anchor and are independently recomposed. An independent set gives every device only the original. Then ask for either the common preset—phone `1440×3200`, iPad `2048×2732`, desktop `3840×2160`, watch `1024×1024`—or labelled custom pixels. Never crop one wallpaper into another or chain derivatives.

5. Start a fresh job and reserve collision-safe output directories before generation. Use only the current invocation's explicit source or theme. Read `references/xxd-panel-041-prompt.en.md` or `references/xxd-panel-041-prompt.zh-CN.md` immediately before building the generation request.
6. Privately lock the principal subject or inseparable relationship, at least three source-specific recognition cues, the style's complete aesthetic motive, composition logic, materials, palette, typography, exact copy, and locale. The source photograph is the factual and identity anchor; do not borrow content from samples or old outputs.
7. Use **single complete-canvas generation as the default for every mode**:
   - `top-bottom`: supply the source as a high-fidelity edit/reference input and generate one finished image containing the faithful source in the upper half and the 041 transformation in the lower half.
   - `left-right`: supply the source as a high-fidelity edit/reference input and generate one finished image containing the faithful source on the left and the 041 transformation on the right.
   - `design-only`: generate the 041 transformation across the whole canvas; the source is reference-only and not visible.
   - `wallpaper-pack`: generate four separate complete canvases, one per device, following the resolved independent or linked relationship.
8. Append the complete-canvas payload below to the full local style prompt. Keep all 041-specific aesthetic and typography instructions active across the entire composition. For paired modes, ask for approximately equal regions while prioritising a coherent finished artwork: colour, light, rhythm, typography, meaning, and any cross-panel echo must feel intentionally unified.
9. Generate each distinct output as a fresh raster image job. Do not request two separate half-images, a contact sheet, a mockup, an empty reserved panel, or a code-rendered substitute.
10. Inspect the actual bitmap at full size and thumbnail size. Check, in order: whole-poster integration; 041 aesthetic fidelity; source identity and structure; visual and semantic correspondence between regions; typography and locale; mode, ratio/pixels, count, and PNG format; then approximate 50/50 geometry.
11. If a paired result fails a hard requirement, retry the **complete canvas once**, changing only the failed constraint. Use `scripts/compose_panel.py` only after that retry still fails, or when the user explicitly requires pixel-identical source preservation, the active image route cannot realise the selected canvas, the requested ratio exceeds route limits, or final lossless pixel calibration is necessary. The script is a fallback utility, never the default creative path and never an aesthetic judge.
12. Reopen every final PNG, apply the acceptance gate, and return absolute paths in source order and mode order 1→4. Wallpaper order is phone, iPad, desktop, watch.

## Complete-canvas generation payload

Append one resolved block to the style prompt for each output:

```text
OUTPUT MODE: TOP_BOTTOM | LEFT_RIGHT | DESIGN_ONLY | WALLPAPER_PACK
DEVICE PROFILE: NONE | PHONE | IPAD | DESKTOP | WATCH
FINAL CANVAS: <whole finished ratio and/or exact WIDTHxHEIGHT>
GENERATION STRATEGY: SINGLE COMPLETE CANVAS
REFERENCE ROLE: SOURCE — HIGH-FIDELITY CONTENT AND IDENTITY ANCHOR
SOURCE VISIBILITY: UPPER 50% | LEFT 50% | REFERENCE ONLY — NOT VISIBLE
LAYOUT RULE:
- Produce one finished poster in one image.
- TOP_BOTTOM keeps a faithful photographic source in the upper half and creates the transformed design in the lower half.
- LEFT_RIGHT keeps a faithful photographic source in the left half and creates the transformed design in the right half.
- DESIGN_ONLY and WALLPAPER_PACK use the whole canvas for the transformed design and show no source photograph or reserved panel.
- Keep paired regions approximately equal while unifying colour, light, rhythm, typography, and meaning.
- Do not output separate panels, a contact sheet, a mockup, or an empty placeholder.
WALLPAPER RELATIONSHIP: NONE | INDEPENDENT | LINKED
ANCHOR DEVICE: NONE | IPAD
```

For text output append:

```text
COPY MODE: REQUIRED
COPY ORIGIN: USER_EXACT | USER_DIRECTION | SOURCE_DERIVED
COPY LOCALE: <resolved locale>
COPY PAYLOAD: <the exact 041-specific title and supporting-text package resolved under the local production prompt>
COPY RULE: Render only the populated strings in COPY PAYLOAD, each exactly once. Do not rewrite, translate, spell-correct, duplicate, or add text. Use native shaping, direction, punctuation, spacing, and semantic line breaks. Preserve the 041-specific hierarchy, amount of supporting text, placement, material, and typographic role instead of applying a generic overlay.
```

For text-free output append only `COPY MODE: NONE — render no text or pseudo-text anywhere.`

## Composition fallback only

`scripts/compose_panel.py` remains available for deterministic recovery and audit. Trigger it only under step 11. When used, generate a same-aspect design asset from the full 041 prompt, preserve the source without destructive crop or stretch, and document which fallback condition applied. A direct complete-canvas success must not be split and recomposed again.

```bash
# Read-only audit after direct generation
python3 scripts/compose_panel.py --audit final.png --layout top-bottom --size WIDTHxHEIGHT

# Deterministic fallback after the complete-canvas retry has failed
python3 scripts/compose_panel.py --source photo.png --design design.png \
  --out final.png --layout top-bottom --size WIDTHxHEIGHT
```

## Output structure

```text
~/Desktop/xxd/xxd-panel-041/<fresh-task>/
└── source-01/
    ├── top-bottom/final.png
    ├── left-right/final.png
    ├── design-only/final.png
    └── wallpaper-pack/phone.png · ipad.png · desktop.png · watch.png
```

Create only selected folders. Return direct PNG paths and a concise count summary. Do not create an automatic combined preview.

## Acceptance gate

- Correct fresh source, selected modes, dimensions, file count, and a visually balanced paired relationship, or exact 50/50 geometry when explicitly required.
- At least three source-specific recognition cues remain; the source-specific chain and every visual-system requirement above are visible.
- Copy is exact, language-native, legible, and structurally integrated; text-free output contains no text or pseudo-text.
- Linked wallpapers share the original source and same approved anchor without derivative chaining; independent wallpapers use only the source.
- Final files are raster PNGs. No SVG/HTML/Canvas/programmatic-art substitute, mockup, overview, UI, watermark, or leaked private route information.

## Override policy

Preserve explicit subject, mode set, output count, exact pixels or ratios, wallpaper relationship, copy mode, exact wording, locale, and intended meaning. User overrides may alter these variables but do not silently authorise abandoning source identity, the 041 aesthetic motive, fresh-task isolation, raster-only output, privacy, or verification. If the user explicitly requests a different aesthetic, acknowledge that it leaves this Skill's style rather than pretending it remains 041.

## References

- Read `references/xxd-panel-041-prompt.en.md` or `references/xxd-panel-041-prompt.zh-CN.md` immediately before generation.
- `references/041-source.md` archives the original style brief and is evidence, not an implicit 3:4 default.
