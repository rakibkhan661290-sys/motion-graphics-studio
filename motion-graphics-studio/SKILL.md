---
name: motion-graphics-studio
description: "Creates content-led motion graphics and animated video, from creative direction and storyboards through production-ready source or render. Use for explainers, kinetic typography, brand or product motion, data stories, posters, logo stings, and social video."
---

# Motion Graphics Studio

Create clear, distinctive motion work from the user's content. Choose the visual theme, motion language, and production method to fit the message, audience, and requested output. Do not force every brief into a preset aesthetic.

## Plan the work

1. Identify the message, audience, intended response, supplied content, destination, duration, aspect ratio, language(s), brand rules, assets, and deliverable. Preserve source meaning; do not invent facts, quotes, product features, or data. Infer practical defaults when details are missing, and ask only when a missing decision would materially change the result.
2. Choose one primary visual direction based on message fit, audience clarity, platform, brand, feasibility, and distinctiveness. State the direction and a short reason. For example, data may benefit from editorial charts; a how-to from diagrams; a product from real or clearly illustrative UI; a personal story from tactile collage; a launch from a distinctive brand motif; and a short social piece from one strong hook. These are prompts for judgment, not a fixed menu.
3. Build an information hierarchy and emotional arc. Organize the story into purposeful beats such as hook or context, development, reveal, and resolution. For multi-scene work, give each beat a time, purpose, visual, on-screen copy, and motion or transition cue. Leave enough time to read and understand.
4. Set the output profile: dimensions, aspect ratio, frame rate, duration, safe areas, captions, audio, and export format. If a named platform's current requirements matter, check official specifications when browsing is available; otherwise state a reasonable assumption. For multiple destinations, recompose for each one instead of relying on a crop.
5. Choose the production level that matches the request: quick concept, timed storyboard or animatic, or full production. Do not inflate a simple request into a large package or stop at a concept when a finished animation was requested.

## Design and animate

- Make typography, palette, composition, texture, and motion feel specific to the subject. Prefer a few meaningful motion ideas over constant effects. Use staging, anticipation, easing, follow-through, pauses, and transitions to direct attention or explain relationships.
- Give kinetic type readable entrances and holds. Preserve exact copy when asked. Animate complete words, phrases, or grapheme clusters when splitting text could break shaping or readability.
- For charts, retain labels, units, axes, and context; preserve proportional accuracy and compare every value against the source. Animate the relationship or takeaway, not only the bars.
- For product and UI work, use supplied screens or accurate product references. Label invented interface states as illustrative; do not imply nonexistent product functionality.
- For logos and brand marks, preserve approved proportions, spacing, and legibility. Hold the final lockup long enough to register.
- For character motion, maintain recognizable design, staging, and screen direction. For 3D, use camera, depth, lighting, and materials to clarify form or set a deliberate mood; avoid movement that only shows off technique.
- For web or interactive animation, make state changes understandable and controls usable without motion. Respect reduced-motion settings.

## Every language and writing system

Support the language and writing system requested by the user, including mixed-language projects. Do not default to English, Latin script, left-to-right layout, or a single universal font.

- Preserve supplied wording, spelling, diacritics, punctuation, and script exactly unless translation or editing is requested. Never silently omit, transliterate, reverse, or replace text to fit a tool. If translation accuracy is important and uncertain, flag it for review.
- Use Unicode-aware text layers, fonts with the needed glyph coverage, and a renderer that shapes the target script correctly. Consider right-to-left and bidirectional ordering for Arabic, Hebrew, and mixed-script lines. Do not reverse strings by hand. Follow script-specific reading order, punctuation, line breaks, spacing, and numeral conventions.
- Keep combining marks, vowel signs, conjuncts, and ligatures intact. Do not stagger or split raw code points; animate complete phrases or safe grapheme clusters.
- Localize captions, dates, units, decimal and grouping separators, and chart labels when appropriate, while keeping underlying facts and values unchanged.
- Render and inspect actual text in every requested script using the chosen production pipeline. Check missing glyphs, shaping, detached marks, punctuation, line breaks, collisions, clipping, and safe areas at intended playback size. If it fails, change the font, text engine, or production path and inspect again.
- Check that voice generation and pronunciation support the requested language before promising localized audio. Keep script and captions aligned to rendered audio. If the available tools cannot produce or verify a language correctly, preserve the original text and deliver the best editable production handoff, clearly stating the limitation.

## Choose tools and produce

Inspect the current project, files, supplied assets, available applications, and render capabilities. Continue an existing project in its established stack when practical. Honor the requested application or format when possible; otherwise choose the simplest suitable available toolchain. Do not assume a proprietary application, dependency, or paid service is available. If no suitable renderer is available, provide a useful honest substitute such as runnable source, a storyboard, or a production specification.

Use these as examples only when that application or project is actually available:

- **After Effects:** Set composition dimensions, frame rate, and duration from the output profile. Check keyframe timing and paths. For a requested reusable Premiere control surface, package a Motion Graphics template when supported and note fonts, plugins, or dependencies.
- **Remotion:** Set composition ID, dimensions, frame rate, and duration in frames. Make repeated variants configurable when useful. Render with the installed project version and inspect the resulting media.
- **Blender:** Set the active camera, frame range, output dimensions, frame rate, and output path. A short preview can catch framing or lighting issues before a full render. Include the editable project when requested or useful.
- **SVG, CSS, or Canvas:** Use for browser-native or interactive work. Check the actual viewport, loaded typography, controls, and reduced-motion behavior. Do not describe an interactive animation as an exported video.

Inventory relevant assets before production. Preserve originals and use clear project-relative paths. Follow supplied brand rules and asset licenses. If a needed asset is unavailable, create an original substitute, use a clearly identified placeholder, or ask for the source when authenticity matters. For projects with multiple assets, include a concise manifest that says what each item is, where it came from, its role, and any credit or license requirement. Do not redistribute third-party fonts or media without rights.

Plan sound when it supports the brief. Map voiceover, music, ambience, and sound effects to story beats. Keep dialogue intelligible and the core message understandable with audio muted; caption speech and meaningful audio cues when needed. Use supplied or properly licensed audio, or create an original direction. Do not claim audio was mixed or embedded unless the result was rendered and checked.

## Accessibility and series continuity

- Keep text legible at real playback size with sufficient contrast. Do not rely on color alone for essential distinctions.
- Avoid strobing, rapid flashing, and unnecessarily intense camera movement. When the brief genuinely requires intense effects, follow applicable current accessibility or platform guidance and consider a safer version or viewer warning.
- Check captions, contrast, type size, and motion at the smallest expected display size. For web output, keep content and controls usable with reduced motion enabled.
- For a recurring series, establish only useful shared rules: palette, type roles, spacing, logo treatment, recurring motifs, transition behavior, timing, sound identity, and naming. If a reusable system or multi-part project needs one, create a concise project-level `motion-bible.md` with approved decisions and separate fixed brand rules from episode choices. Keep it consistent when revising the series.

## Review, revise, and hand off

Before delivery, inspect the opening, densest information moment, major transition, and ending at intended playback size. Check timing, hierarchy, copy, safe areas, sound, accessibility, continuity, and factual accuracy. For data or instructional work, compare labels and values with the source. Confirm an export's existence, playback, duration, dimensions, frame rate, and audio when tools allow. For interactive work, exercise its main interaction and viewport behavior. Inspect actual rendered text for every requested script, not only the editor view.

When feedback arrives, translate it into a concrete change, preserve approved elements, and revise only what is needed. Recheck the changed scene and any affected transitions, captions, audio, or alternate formats. Return the updated preview or source and summarize the revision. Ask for feedback at a useful review point, but do not make feedback a prerequisite when the brief is already clear.

Provide only useful handoff items for the requested scope: final render or preview, editable source, required assets, timed storyboard, motion notes, captions or voiceover script, render settings, dependencies, and attribution. Keep paths understandable and verify project references when possible. State any missing dependency or unverified output plainly. Never claim to have rendered, previewed, or exported media unless it succeeded and was checked.

Match the user's language in discussion and use the requested language(s) for voiceover, captions, and on-screen text. Do not assume personal preferences persist across chats or platforms. Use a separate `motion-profile.md` only when supplied or requested, and record confirmed preferences rather than inventing them.
