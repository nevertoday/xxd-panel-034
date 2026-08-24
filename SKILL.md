---
name: xxd-panel-034
description: "Create XXD Panel 034 artwork from supplied photos in four combinable modes: photo above/multicolour rubber-stamp field note below, photo left/design right, design alone, or a four-device wallpaper pack with independent or anchor-linked continuity. Reduces the source to one small recognisable hand-carved stamp using two to four source-derived spot inks, broken impression, slight misregistration, warm fibrous paper, generous whitespace, and quiet typewriter field annotation. Use for the exact 034 travel-observation rubber-stamp style; never use it for souvenir stamps, postage templates, round seals, sticker collages, cartoons, smooth vectors, or decorative travel branding."
---

# XXD Panel 034 · 多色橡皮章旅行田野注释

Turn each supplied photograph into one quiet, collectible field-note design. Preserve the real photograph only in paired modes. Reduce the source's defining subject, contour, pose, direction, spatial relation, and narrative feature into one small multicolour rubber-stamp image. Two to four source-derived spot inks, uneven hand-cut lines, broken impression, exposed paper, chipped edges, pressure variation, slight registration drift, warm fibrous paper, generous whitespace, and restrained field annotation make the stamp feel observed and hand-printed rather than templated.

Operational rules follow the shared XXD Panel workflow contract: four combinable modes; one or more explicitly confirmed whole-canvas ratios or exact resolutions before generation; single complete-canvas raster generation by default; high-fidelity source reference in paired modes; linked or independent four-device wallpapers; copy and locale preflight; fresh generation jobs; privacy-preserving raster generation; deterministic composition as fallback only; and one fresh task directory per source and mode. Style-specific sections refine aesthetics and copy but never override this contract.

## Non-negotiable contract

- One input may use one or more selected modes and one or more ordinary-output sizes. Each selected ordinary mode (`top-bottom`, `left-right`, `design-only`) produces one PNG for every deduplicated selected size. `wallpaper-pack` is a separate device-specific branch: it produces four PNGs by default, one per device, and is not multiplied by the ordinary size set. Multiple resolutions for a named device are allowed only when explicitly requested. With one ordinary size, selecting all four modes still produces seven files; otherwise calculate and state the total before generation. Keep modes, inputs, and wallpaper files isolated and never combine them into a grid, contact sheet, overview, collage, or mockup.
- Resolve a non-empty ordered set of modes before generation: `top-bottom`, `left-right`, `design-only`, and/or `wallpaper-pack`. Accept one choice, multiple choices separated by `+`, Chinese/English commas or whitespace, natural-language names, or `全部` / `all`. Deduplicate repeated choices and execute in menu order 1→4. If none is specified, ask with the multiline multi-select menu in the workflow. Do not ask again when the set is already clear.
- When the selected set contains `wallpaper-pack`, require a second choice: `linked` or `independent`. A linked pack approves one anchor wallpaper, iPad by default, and makes every other device reference both the original photo and that same anchor. An independent pack gives every device only the original photo. Neither permits resizing or cropping one wallpaper into the others. Do not ask this follow-up when wallpaper mode is not selected.
- Paired modes target a visually equal 50/50 relationship within one coherent generated canvas. Minor generative deviation is acceptable unless the user explicitly requires pixel-exact halves; exact deterministic geometry belongs to the documented fallback. `design-only` and every wallpaper contain no visible source photograph, no seam, and no reserved photographic panel.
- Before ordinary-mode generation, resolve a non-empty ordered set of one or more whole final-canvas targets. Offer a source- and mode-aware recommendation with its explicit ratio and common pixels, source aspect as an explicit choice, a finite set of common aspect-ratio cards, and custom ratios or exact pixels. Never silently infer or force a final canvas; exact pixels take precedence over a ratio.
- Different aspect ratios are separate complete-canvas compositions and must be independently recomposed from the same source and full local aesthetic prompt. Multiple pixel sizes with the same aspect may share the highest-quality approved composition and be exported to each exact target. Resolve `auto` and `source`, deduplicate identical targets, preserve the user's order, and state the resulting output count before generation.
- For user-facing preflight, prefer genuine native interactive controls when exposed: multi-select for modes and ordinary sizes, single-select for copy mode and wallpaper relationship, and free input for custom values. If unavailable, use a clear multiline numbered fallback and accept numbers, natural language, or inline parameters. Never present non-interactive symbols as clickable checkboxes, and never ask again for a variable already resolved.
- Visible photography remains faithful. Allow only restrained editorial grading and environmental extension needed for an explicitly overridden canvas. Never stretch, distort, repaint, replace, or structurally alter the subject.
- The transformed frame must preserve identity, direction, spatial relation, and narrative through at least three source-specific cues while reducing the source to one small hand-carved multicolour rubber stamp on warm light paper. It is not a souvenir, postage stamp, passport mark, round seal, sticker, generic travel badge, smooth vector filter, cartoon, commercial logo, or decorative collage.
- Copy has no silent default. Resolve automatic copy, exact custom copy, or text-free output before image generation. Automatic and custom modes also require a target language or locale. By default, one source-specific copy package is shared verbatim across all selected modes; explicit per-mode copy instructions override it.
- Render no logo, watermark, signature, colour swatch, UI, device mockup, decorative pseudo-text, or unrelated explanatory prose.

## Aesthetic motive lock

Modes and device ratios may change placement and aspect ratio but never the 034 motive. Every transformed frame must visibly express this chain:

**this exact photographed subject or inseparable relation → preserve at least three defining cues across contour, pose, direction, proportion, opening, overlap, distance, and narrative → delete irrelevant detail → rebuild one recognisable small rubber-stamp motif with silhouette, spot-colour blocks, cut marks, and limited overlap → choose two to four source-derived spot inks → print with uneven pressure, broken ink, exposed paper, chipped edges, grain, and slight registration drift → place the stamp freely but deliberately within generous warm-paper whitespace → align one quiet field title, an honest record number when available, and only useful keywords or notes to the stamp edge, baseline, whitespace, or local contour**.

The collectible quality comes from the tension between one small imperfect hand impression and a large calm paper field, not from adding travel emblems. Rubber carving, field notebooks, travel observation, typewriter labels, and small independent print editions are material disciplines rather than a souvenir template library.

Reject the result as generic when an unrelated photo could replace the source without materially changing the stamp contour, retained cues, spot-ink separation, placement, whitespace relation, cut-line direction, or annotation. Also reject circular seal defaults, perforated postage borders, passport marks, tourist badges, stickers, many scattered stamps, clip art, smooth vector edges, fixed travel palettes, faux-aged dirt, cartoon craft, and decorative metadata.

## 034 visual system

### One small recognisable stamp

- Privately lock at least three source-specific cues across contour, pose/orientation, function, proportion, material, colour, opening, connection, overlap, negative shape, or relationship distance.
- Delete irrelevant detail and retain only the structure, direction, silhouette, opening, overlap, distance, and narrative relation that make the source memorable.
- People keep pose, direction, clothing mass, and relational distance; animals keep body rhythm and head direction; plants keep growth gesture; architecture keeps skyline and defining openings; objects and vehicles keep functional silhouette and negative shape; landscapes keep one source-specific terrain or spatial relation.
- Translate with silhouette, spot-colour blocks, uneven carved lines, negative cuts, and only limited overlaps. Recognition must survive the small stamp scale.

### Small scale and large field

- Keep the stamp small or modest relative to the canvas and protect a large, active warm-paper field around it.
- Let source direction, aspect, and visual weight decide placement. Off-centre, near-edge, and source-earned partial crop are allowed; automatic centring is not required.
- Establish one clear centre of gravity and a quiet editorial balance. One stamp remains the primary object; do not distribute many equal stamps or fill the page.
- Align annotation to an actual stamp edge, baseline, local contour, or whitespace axis. The connection should feel observed, not decorated.

### Hand-carved and hand-printed evidence

- Show uneven cut-line width, small gouge marks, broken ink, granular deposits, paper show-through, chipped edges, pressure variation, and slight misregistration between spot colours.
- Preserve the decisive contour and source identity even when the impression is incomplete. Wear follows carved and printed structure rather than random grunge.
- Use solid relief areas, carved negative lines, selective overprint, and believable contact pressure rather than realistic modelling or a filter laid over vector art.
- Reject uniform digital distress, blurred photocopy noise, dirty vintage overlays, smooth vector perfection, thick 3D embossing, and children's craft roughness.

### Warm paper and source-derived spot inks

- Use warm white, light oat, pale cream, or another source-compatible light paper with subtle fibres and no heavy vintage staining.
- Select two to four of the current photograph's most recognisable colours as spot inks. Assign each one a structural region, layer, or emphasis; do not imitate every source hue.
- Build depth through controlled separation, overlap, value, and slight registration shift. Each ink remains clean enough to feel deliberately mixed and printed.
- Avoid fixed travel colour cards, decorative rainbow separation, gradients, neon, universal beige, muddy ageing, and colour unrelated to recognition.

## Copy behaves like field annotation

034 text behaves like a traveller's or observer's field annotation attached to the stamp and paper—not a commercial headline, tourism slogan, museum UI, detached caption block, or decorative archive costume.

- Automatic copy derives one concise title from a verified place, subject, state, action, or supported image; it never invents provenance or a picturesque backstory.
- Prefer one restrained title plus two or three grounded keywords or one extremely short note. `No.` appears only when provided, reliably established, or transparently assigned as the current batch sequence; it never pretends to be historical metadata.
- Preserve exact user wording verbatim. Refine an editable direction only within permission while protecting audience, mandatory terms, tone, and semantic phrase breaks.
- Apply the unrelated-image swap test: generic lifestyle words that survive on another source must be rewritten.

Typography has its own 034 construction:

- **Role:** a quiet record layer that makes the stamp feel observed and catalogued.
- **Voice:** concise, factual, attentive, modest, and contemporary.
- **Construction:** one short title plus two or three grounded keywords or one tiny note; the stamp remains the visual centre.
- **Placement:** align with a stamp edge, baseline, local contour, or active whitespace axis.
- **Material:** small typewriter or archival microtype with restrained impression variation; never a huge headline, travel-script font, faux passport type, or costume label.
- **Script:** use native construction, joining, direction, punctuation, spacing, and legibility for the resolved Chinese, Japanese, Korean, Arabic, or Latin locale.

Resolve locale independently from command language:

```text
target market or audience > requested output language > direction language; if none is explicit, ask before generation
```

Localise by transcreation using native wording, rhetoric, punctuation, spacing, shaping, and semantic line breaks. Never infer nationality or audience language from appearance, clothing, scenery, filenames, metadata, or signs.

## Raster generation and privacy

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is exposed through the host's built-in image tool or an already configured compatible route, use it before any other model. Preserve the current XXD execution contract: resolve the whole final canvas before generation, use the source as a high-fidelity reference, generate paired modes as one complete canvas, and keep deterministic composition as fallback only.
- Also support **Seedance 5.0 Pro**, **Nano Banana Pro (Gemini Image Pro)**, **Nano Banana 2 (Gemini Image Flash)**, or another compatible bitmap model when it is actually available through a tool or configured route and can satisfy the selected mode. Required capabilities include reference-image generation/editing, source fidelity, the resolved whole-canvas ratio, native target-language text, and multi-image reference input when a linked wallpaper pack needs it.
- Alternative models are secondary routes, not a different workflow. Do not let a model switch silently change the selected modes, final canvas, source-visibility rules, copy, locale, wallpaper relationship, fresh-task boundary, raster-only delivery, or the full-canvas-first strategy. If an alternative cannot satisfy a hard requirement, do not silently degrade that requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. A user may voluntarily provide credentials for the current task. Accept them without echoing, displaying, logging, or reporting their value. Do not persist credentials or modify provider, account, billing, or global route configuration unless the user explicitly asks for that configuration change.
- Determine availability from an actual image-capability check. Do not declare GPT Image 2 or every other route unavailable merely because one tool is absent, one call failed, or one expected environment variable is unset.

Prefer GPT Image 2 through the host's built-in bitmap image-generation capability when exposed, and follow the available `imagegen` skill for the built-in execution details. View each local source before generation. Use one generation call per distinct asset; a wallpaper pack requires four calls. “Rubber stamp”, “spot ink”, “carved line”, “misregistration”, “paper fibre”, and “typewriter annotation” describe raster image appearance only and never authorise SVG, HTML, CSS, Canvas, diagrams, or programmatic drawing as the artwork.

If built-in bitmap generation is unavailable, use `scripts/configured_imagegen.py`, which reuses an already configured compatible bitmap route and emits sanitised status only:

```bash
python3 scripts/configured_imagegen.py probe
python3 scripts/configured_imagegen.py edit --image source.png \
  --prompt-file /private/job-temp/transform-prompt.txt \
  --out /private/job-temp/design.png --size 1536x1024 --quality high
```

Judge readiness by actual bitmap capability, not a provider name or one environment variable. Never display, echo, log, or report the user's actual provider, endpoint, headers, credential values, account identifiers, route configuration, prompts, or response bodies. Do not manually inspect unrelated credential files. Do not persist user-provided credentials or modify global route configuration unless explicitly requested. The bridge's sanitised JSON is the complete allowed diagnostic surface.

An explicit invocation of `/xxd-panel-034` or `$xxd-panel-034` with a source image and requested output authorises generation through any already configured authenticated bitmap route available to the session. Do not ask for a second confirmation solely because the route changes. This does not authorise changing credentials, providers, billing, accounts, or global settings.

Only report generation as unavailable after checking preferred GPT Image 2, every eligible exposed alternative, the bundled probe, and any suitable route or API key the user elects to provide. State the limitation narrowly and never guess the cause or expose the user's actual provider. Never substitute code-rendered art.

## Fresh-task and source boundary

Every invocation starts a fresh generation job unless the user explicitly asks to continue, audit, compare, edit, or reuse a named earlier result. Repeating the same source and parameters still means generating a new result in a new task directory. An old file can never satisfy a new request.

Use only images attached to the current invocation, explicit user paths, or a previously supplied image that the current request clearly identifies as “the same image”. Never broadly scan the Desktop, workspace, `~/Desktop/xxd/xxd-panel-034/`, or historical task folders to find a substitute source. If the intended source cannot be accessed, ask for it.

## Workflow

### Inline-parameter fast path

Parse explicit `--parameters` anywhere after the invocation and source/input. Every user-facing setting is a variable:

```text
/xxd-panel-034 <source> \
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

   1. 上下对照（原图在上，034 设计在下）
   2. 左右对照（原图在左，034 设计在右）
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
      我根据原图和 034 的气质创作；请注明语言或地区
   2. 使用你的文案
      请发送需要出现的准确文字，并注明语言或地区
   3. 不要文字

   回复示例：尺寸 4+10，文字 1，日语
   回复示例：尺寸 6，文字 2，英式英语，STILL IN BLOOM
   ```

   If a native form supports multiple controls, show size multi-select and copy-mode single-select together. Collect locale in the same form or ask one short conditional follow-up. Automatic copy must be source-specific and native to the resolved locale. Preserve exact custom copy verbatim. Never infer locale from appearance, clothing, scenery, filenames, metadata, or visible signs.

4. Only when `wallpaper-pack` is selected, resolve its single-choice relationship: `连贯套装` or `四张独立`. Explain `连贯套装` as one approved visual direction independently recomposed for four devices—not one image cropped four ways. Then resolve either the common device preset—phone `1440x3200`, iPad `2048x2732`, desktop `3840x2160`, watch `1024x1024`—or labelled custom pixels. Ordinary size selections do not multiply wallpaper outputs. By default the pack has one target per device; accept multiple labelled resolutions for a device only when the user explicitly requests variants. Never crop one wallpaper into another or chain derivatives.

   Before generation, state a concise execution summary: selected modes, concrete size targets, copy mode and locale, wallpaper relationship, and total output count. Do not require another confirmation when the information is complete and consistent; begin immediately. The default count is `ordinary mode-size assignments + four wallpaper files`, adjusted only for explicitly requested wallpaper resolution variants.

5. Start a fresh job and reserve collision-safe output directories before generation. Use only the current invocation's explicit source or theme. Read `references/xxd-panel-034-prompt.en.md` or `references/xxd-panel-034-prompt.zh-CN.md` immediately before building the generation request.
6. Privately lock the principal subject or inseparable relationship, at least three source-specific recognition cues, the style's complete aesthetic motive, composition logic, materials, palette, typography, exact copy, and locale. The source photograph is the factual and identity anchor; do not borrow content from samples or old outputs.
7. Use **single complete-canvas generation as the default for every mode**:
   - `top-bottom`: supply the source as a high-fidelity edit/reference input and generate one finished image containing the faithful source in the upper half and the 034 transformation in the lower half.
   - `left-right`: supply the source as a high-fidelity edit/reference input and generate one finished image containing the faithful source on the left and the 034 transformation on the right.
   - `design-only`: generate the 034 transformation across the whole canvas; the source is reference-only and not visible.
   - `wallpaper-pack`: generate four separate complete canvases, one per device, following the resolved independent or linked relationship.
8. Append the complete-canvas payload below to the full local style prompt. Keep all 034-specific aesthetic and typography instructions active across the entire composition. For paired modes, ask for approximately equal regions while prioritising a coherent finished artwork: colour, light, rhythm, typography, meaning, and any cross-panel echo must feel intentionally unified.
9. Generate each distinct output as a fresh raster image job. Do not request two separate half-images, a contact sheet, a mockup, an empty reserved panel, or a code-rendered substitute.
10. Inspect the actual bitmap at full size and thumbnail size. Check, in order: whole-poster integration; 034 aesthetic fidelity; source identity and structure; visual and semantic correspondence between regions; typography and locale; mode, ratio/pixels, count, and PNG format; then approximate 50/50 geometry.
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
COPY PAYLOAD: <the exact 034-specific title and supporting-text package resolved under the local production prompt>
COPY RULE: Render only the populated strings in COPY PAYLOAD, each exactly once. Do not rewrite, translate, spell-correct, duplicate, or add text. Use native shaping, direction, punctuation, spacing, and semantic line breaks. Preserve the 034-specific hierarchy, amount of supporting text, placement, material, and typographic role instead of applying a generic overlay.
```

For text-free output append only `COPY MODE: NONE — render no text or pseudo-text anywhere.`

## Composition fallback only

`scripts/compose_panel.py` remains available for deterministic recovery and audit. Trigger it only under step 11. When used, generate a same-aspect design asset from the full 034 prompt, preserve the source without destructive crop or stretch, and document which fallback condition applied. A direct complete-canvas success must not be split and recomposed again.

```bash
# Read-only audit after direct generation
python3 scripts/compose_panel.py --audit final.png --layout top-bottom --size WIDTHxHEIGHT

# Deterministic fallback after the complete-canvas retry has failed
python3 scripts/compose_panel.py --source photo.png --design design.png \
  --out final.png --layout top-bottom --size WIDTHxHEIGHT
```

## Output location

Save finished work under `~/Desktop/xxd/xxd-panel-034/` unless the user supplies another destination. Create the shared `~/Desktop/xxd/` wrapper, the skill root, and each task directory when needed.

- Wrap every source-and-mode result in a fresh task directory: `<source-stem>-top-bottom/`, `<source-stem>-left-right/`, `<source-stem>-design-only/`, or `<source-stem>-wallpaper-pack/`.
- A batch or multi-select creates one sibling task directory per source and selected mode. Never mix sources or modes.
- An ordinary-mode task directory contains one final PNG per selected size. Keep the existing base name for a single target; for multiple targets append a stable label such as `-3x4-1536x2048`, `-9x16-1440x2560`, or `-custom-2160x3840` so every deliverable is unambiguous.
- The final count per source equals the sum of ordinary mode-size assignments plus four wallpaper files by default, adjusted only for explicitly requested per-device wallpaper variants. State this count before generation.
- A wallpaper task directory contains four finished PNGs by default, named `<source-stem>-wallpaper-phone.png`, `-ipad.png`, `-desktop.png`, and `-watch.png`; explicitly requested resolution variants add their size label to the filename. Do not create device subdirectories.
- Never overwrite. Append `-2`, `-3`, and so on to a colliding task-directory name while keeping filenames unchanged.
- Keep prompts, intermediate generations, plans, audits, and source copies outside the finished task directory.

## Acceptance gate

Before accepting each result verify:

- Mode, exact pixels, explicit final-canvas ratio or pixels, split axis, seam, and output count are correct.
- Visible photography is faithful and type-free; source-hidden outputs contain no source photograph or seam.
- The small stamp remains recognisable through at least three source-specific cues; irrelevant detail is removed without erasing direction, relation, or narrative.
- The stamp-to-paper scale creates generous active whitespace; placement follows source direction and visual weight rather than a souvenir template.
- Two to four source-derived spot inks have clear structural jobs and believable overlap; no fixed travel palette or decorative rainbow survives.
- Uneven carving, broken ink, paper show-through, grain, chipped edges, pressure variation, and slight misregistration feel physically printed while the key contour remains readable.
- The overall result is quiet, modest, tactile, and collectible: a field observation rather than a postage stamp, passport mark, tourism badge, sticker, cartoon, or digital filter.
- Automatic copy is a grounded field title with only useful keywords, note, or honest sequence number. Exact user copy remains verbatim. All rendered text is accurate and native to the resolved locale; text-free output contains no text or pseudo-text.
- Small typewriter or archival microtype aligns with the stamp edge, baseline, contour, or whitespace and never becomes a commercial title or faux passport label.
- Every wallpaper is separately recomposed, respects safe regions, contains no system UI, and is not a crop of another device result. A linked pack shares one family without drifting from the source.
- Every delivered PNG was newly generated for this invocation and lives in its fresh task directory.

## Override policy

Preserve user-specified source, mode set, output count, dimensions, target locale, copy mode, and exact finished wording. Priority is explicit text-free request > exact user wording > editable user direction > source-derived automatic copy. Exact pixels take precedence over an explicitly chosen ratio; neither may be inferred silently. A labelled wallpaper size overrides only that device.

User instructions may change motif emphasis, stamp scale, placement, spot-ink balance, overlap, crop, whitespace, impression wear, annotation relation, or copy within 034, but do not silently relax one-photo isolation, exact paired geometry, four separate wallpaper outputs, fresh-task generation, source-hidden output rules, or native-language typography. Leave the small multicolour rubber-stamp field-note aesthetic only when the user explicitly asks to leave the 034 style.

## Provenance boundary

The user's original style brief is archived at [references/034-source.md](references/034-source.md). It records the initial 3:4 top-bottom example but does not override the operative mode and explicit final-canvas selection and complete-canvas generation rules. The full local 034 prompt is the production specification. Never borrow subjects, colours, copy, or compositions from samples or previous outputs.
