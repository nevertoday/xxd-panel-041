---
name: xxd-panel-041
description: "Create XXD Panel 041 artwork from supplied photos in four combinable modes: photo above/luminous Japanese-colour isometric editorial model embedded in a source-earned metaphor and surrounded by faint research sketches below, photo left/design right, design alone, or a four-device wallpaper pack with independent or anchor-linked continuity. Use for the exact 041 style; reject generic 3D model, game diorama, engineering axonometric drawing, low-poly cartoon, metaphor added as decoration, dominant manuscript clutter, heavy shadows, plastic material, mechanical centring, e-commerce display, template composition."
---

# XXD Panel 041 · 主题隐喻等距模型与研究手稿

Rebuild the source as one clear isometric editorial model whose blocks, cuts, levels, and spatial relations preserve identity. A single geometric metaphor becomes its base, gap, path, enclosure, or negative shape, while faint Leonardo-like studies reveal the thinking around the finished form.

Operational rules follow the shared XXD Panel workflow contract: four combinable modes; one or more explicitly confirmed whole-canvas ratios or exact resolutions before generation; single complete-canvas raster generation by default; high-fidelity source reference in paired modes; linked or independent four-device wallpapers; copy and locale preflight; fresh generation jobs; privacy-preserving raster generation; deterministic composition as fallback only; and one fresh task directory per source and mode. Style-specific sections refine aesthetics and copy but never override this contract.

## Non-negotiable contract

- One input may use one or more selected modes and one or more ordinary-output sizes. Each selected ordinary mode (`top-bottom`, `left-right`, `design-only`) produces one PNG for every deduplicated selected size. `wallpaper-pack` is a separate device-specific branch: it produces four PNGs by default, one per device, and is not multiplied by the ordinary size set. Multiple resolutions for a named device are allowed only when explicitly requested. With one ordinary size, selecting all four modes still produces seven files; otherwise calculate and state the total before generation. Keep modes, inputs, and wallpaper files isolated and never combine them into a grid, contact sheet, overview, collage, or mockup.
- Resolve a non-empty ordered set of modes. Accept one choice, multiple choices separated by `+`, Chinese/English commas or whitespace, natural-language names, or `全部` / `all`; deduplicate and execute in menu order 1→4.
- If `wallpaper-pack` is selected, resolve `linked` or `independent`. A linked pack approves one iPad anchor by default, then every other device references the original source plus that same anchor. An independent pack gives every device only the original. Never crop one wallpaper into another and never chain derivatives.
- Paired modes target a visually equal 50/50 relationship within one coherent generated canvas. Minor generative deviation is acceptable unless the user explicitly requires pixel-exact halves; exact deterministic geometry belongs to the documented fallback. `design-only` and every wallpaper show no source photo, seam, or reserved photographic panel.
- Before ordinary-mode generation, resolve a non-empty ordered set of one or more whole final-canvas targets. Offer a source- and mode-aware recommendation with its explicit ratio and common pixels, source aspect as an explicit choice, a finite set of common aspect-ratio cards, and custom ratios or exact pixels. Never silently infer or force a final canvas; exact pixels take precedence over a ratio.
- Different aspect ratios are separate complete-canvas compositions and must be independently recomposed from the same source and full local aesthetic prompt. Multiple pixel sizes with the same aspect may share the highest-quality approved composition and be exported to each exact target. Resolve `auto` and `source`, deduplicate identical targets, preserve the user's order, and state the resulting output count before generation.
- For user-facing preflight, prefer genuine native interactive controls when exposed: multi-select for modes and ordinary sizes, single-select for copy mode and wallpaper relationship, and free input for custom values. If unavailable, use a clear multiline numbered fallback and accept numbers, natural language, or inline parameters. Never present non-interactive symbols as clickable checkboxes, and never ask again for a variable already resolved.
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

### Inline-parameter fast path

Parse explicit `--parameters` anywhere after the invocation and source/input. Every user-facing setting is a variable:

```text
/xxd-panel-041 <source> \
  --mode top-bottom,design-only \
  --size auto,3:4,9:16,2160x3840 \
  --text auto --locale ja-JP
```

- `--mode`: `top-bottom`, `left-right`, `design-only`, `wallpaper-pack`; comma-separated values and repeated flags accumulate.
- `--size`: `auto`, `source`, any listed ratio, or exact `WIDTHxHEIGHT`; comma-separated values and repeated flags accumulate and deduplicate. Accept `×` as well as `x`.
- `--text`: `auto`, `custom`, or `none`. `--copy "..."` supplies exact custom copy and implies `--text custom`; `--locale` accepts a language, market, or locale tag.
- `--wallpaper`: `linked` or `independent`. `--wallpaper-size` accepts labelled device targets such as `phone=1440x3200,ipad=2048x2732,desktop=3840x2160,watch=1024x1024` and may repeat a device for explicit variants.
- `--out` overrides the default output destination.
- Explicit parameters override ambiguous prose. Repeated multi-value parameters accumulate; repeated single-value parameters use the last explicit value. If explicit parameters contradict each other—for example `--text none` with `--copy`—ask only about that conflict instead of silently discarding information.
- When all required variables are supplied, skip the entire preflight and start the fresh generation job. When parameters are partial, ask only for unresolved variables. Never repeat a question already answered by parameters or clear natural language.

### Interactive preflight

Prefer the host's real interactive controls when exposed. Use multi-select controls for modes and ordinary sizes, single-select controls for copy mode and wallpaper relationship, and free input for custom copy, locale, ratios, or pixels. If the host cannot provide a genuinely interactive control with the required choices, use the multiline numbered fallback below. Never show fake checkboxes that look clickable but are not.

1. Resolve one or more modes. In a native multi-select use these human-facing labels: `上下对照`, `左右对照`, `只要设计图`, and `四端壁纸`. If no real multi-select exists, ask and wait:

   ```text
   请选择一个或多个成品类型：

   1. 上下对照（原图在上，041 设计在下）
   2. 左右对照（原图在左，041 设计在右）
   3. 只要设计图（成品中不显示原图）
   4. 四端壁纸
      手机、iPad、电脑、儿童手表各一张

   回复示例：1｜1+3｜1、2、4｜全部
   ```

2. For every selected ordinary mode, resolve one or more whole-finished-canvas targets. First inspect the input and privately calculate a source- and mode-aware recommendation. A recommendation must display its actual ratio, common pixel target, and a short reason; never present an unexplained `自动` choice. `top-bottom` will often recommend `3:4 | 1536x2048`; `left-right` will often recommend `3:2 | 2400x1600`; `design-only` must respond to the source orientation, subject, negative space, and intended use.

   When a native selector can expose the full set, show visual aspect-ratio cards similar to the host's image-size picker and allow multiple cards to be selected. Use these finite choices:

   - `自动适配` — display the resolved recommendation per selected mode
   - `跟随原图比例`
   - `1:1 | 2048x2048`
   - `3:4 | 1536x2048`
   - `4:3 | 2048x1536`
   - `4:5 | 1600x2000`
   - `5:4 | 2000x1600`
   - `2:3 | 1600x2400`
   - `3:2 | 2400x1600`
   - `9:16 | 1440x2560`
   - `16:9 | 2560x1440`
   - `21:9 | 2520x1080`
   - `5:7 | 1600x2240`
   - `7:5 | 2240x1600`
   - `自定义` — accept one or more ratios and/or exact pixel targets

   If a real multi-select is unavailable, include the exact recommendation in option 1 and ask with this multiline fallback:

   ```text
   请选择一个或多个成品尺寸：
   这里选择的是整张最终成品，可以多选。

   1. 自动适配
      本次推荐：<逐个写出所选模式的比例、像素和简短原因>
   2. 跟随原图比例
   3. 1:1｜2048×2048
   4. 3:4｜1536×2048
   5. 4:3｜2048×1536
   6. 4:5｜1600×2000
   7. 5:4｜2000×1600
   8. 2:3｜1600×2400
   9. 3:2｜2400×1600
   10. 9:16｜1440×2560
   11. 16:9｜2560×1440
   12. 21:9｜2520×1080
   13. 5:7｜1600×2240
   14. 7:5｜2240×1600
   15. 自定义比例或准确像素

   回复示例：1｜4+10｜3、6、11｜15：5:8、2160×3840
   ```

   A selected size set applies to every selected ordinary mode unless the user maps targets per mode. Accept mappings such as `上下对照：3:4、9:16；只要设计图：1:1`. Resolve `auto` and `source` to concrete targets, then deduplicate. Every different aspect ratio requires an independently recomposed complete canvas; never crop one ratio into another. Multiple pixel resolutions with the same aspect may share the highest-quality approved composition and be exported at each exact size.

3. In the same second-round preflight when the interface permits it, resolve copy mode and locale. Copy mode is single-select:

   ```text
   请选择文字方式：

   1. 自动文案
      我根据原图和 041 的气质创作；请注明语言或地区
   2. 使用你的文案
      请发送需要出现的准确文字，并注明语言或地区
   3. 不要文字

   回复示例：尺寸 4+10，文字 1，日语
   回复示例：尺寸 6，文字 2，英式英语，STILL IN BLOOM
   ```

   If a native form supports multiple controls, show size multi-select and copy-mode single-select together. Collect locale in the same form or ask one short conditional follow-up. Automatic copy must be source-specific and native to the resolved locale. Preserve exact custom copy verbatim. Never infer locale from appearance, clothing, scenery, filenames, metadata, or visible signs.

4. Only when `wallpaper-pack` is selected, resolve its single-choice relationship: `连贯套装` or `四张独立`. Explain `连贯套装` as one approved visual direction independently recomposed for four devices—not one image cropped four ways. Then resolve either the common device preset—phone `1440x3200`, iPad `2048x2732`, desktop `3840x2160`, watch `1024x1024`—or labelled custom pixels. Ordinary size selections do not multiply wallpaper outputs. By default the pack has one target per device; accept multiple labelled resolutions for a device only when the user explicitly requests variants. Never crop one wallpaper into another or chain derivatives.

   Before generation, state a concise execution summary: selected modes, concrete size targets, copy mode and locale, wallpaper relationship, and total output count. Do not require another confirmation when the information is complete and consistent; begin immediately. The default count is `ordinary mode-size assignments + four wallpaper files`, adjusted only for explicitly requested wallpaper resolution variants.

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
    ├── top-bottom/<size-label>.png
    ├── left-right/<size-label>.png
    ├── design-only/<size-label>.png
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
