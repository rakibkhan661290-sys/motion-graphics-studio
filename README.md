# Motion Graphics Studio

**A multilingual, content-led motion graphics skill for Claude, ChatGPT, and compatible agent tools.** It helps turn a brief into a fitting visual direction, storyboard, animation, and practical handoff.

**বহুভাষিক মোশন গ্রাফিক্স তৈরির জন্য Claude, ChatGPT ও উপযোগী AI agent-এর skill।** কনটেন্ট অনুযায়ী visual direction, storyboard, animation এবং ব্যবহারযোগ্য handoff তৈরিতে সাহায্য করে।

## Download

- **Claude upload package:** [motion-graphics-studio.skill](motion-graphics-studio.skill)
- **Portable ZIP package:** [motion-graphics-studio.zip](motion-graphics-studio.zip)
- **Readable source instructions:** [motion-graphics-studio/SKILL.md](motion-graphics-studio/SKILL.md)
- **Example prompts:** [examples/prompts.md](examples/prompts.md)

The `.skill` file is the same skill bundle as the ZIP, with the extension used by some Claude skill repositories. If an upload screen does not accept `.skill`, use the `.zip` file. The bundle contains a folder named `motion-graphics-studio` with one self-contained `SKILL.md`.

## Install

### Claude

1. In Claude, enable **Code execution and file creation** in **Settings → Capabilities** if it is off.
2. Open **Customize → Skills → + → Create skill → Upload a skill**.
3. Upload `motion-graphics-studio.skill`; if the file picker rejects it, upload `motion-graphics-studio.zip` instead.
4. Turn the skill on in your Skills list.

Claude's interface and access can vary by plan and workspace. The portable ZIP is a skill-folder archive containing `SKILL.md`.

### ChatGPT

1. Open **Plugins → Plugin Directory → Skills → Create → Upload from your computer**.
2. Upload `motion-graphics-studio.zip` and enable it after ChatGPT finishes its scan.

Native Skills upload depends on account eligibility and workspace settings. If Skills is not available, use the `SKILL.md` text as instructions in a Custom GPT or project where that feature is available.

### Claude Code

Copy the `motion-graphics-studio` folder into `~/.claude/skills/` for your user, or `.claude/skills/` in a project. Keep `SKILL.md` inside the folder.

## Use

Ask naturally, for example:

- “Create a 20-second Bangla explainer about how solar panels produce electricity. Give me the storyboard and render it if the available tools support that.”
- “Make a 7-second Arabic-English science event poster. Preserve the exact copy and make both lines readable.”
- “Turn these three supplied values into a 12-second chart animation. Do not infer why the values differ.”
- “Create a calm product feature animation in Spanish, with editable source and captions.”

The skill chooses a content-led theme, respects the requested language and brand, and matches the production path to the tools that are actually available. Rendering still depends on the applications, runtime, assets, and permissions available in the user's environment; the skill does not bundle After Effects, Remotion, Blender, or other render software.

## What it covers

- Creative direction, story beats, timed storyboards, and animation planning
- Multilingual and mixed-script typography, including right-to-left layout and script-aware QA
- Motion craft, charts, product/UI animation, 2D/3D approaches, and sound planning
- Accessibility, series continuity, asset rights, revisions, and editable handoff
- Tool-aware workflows for After Effects, Remotion, Blender, SVG, CSS, and Canvas

## Repository layout

```text
motion-graphics-studio/
  SKILL.md
examples/
  prompts.md
motion-graphics-studio.skill
motion-graphics-studio.zip
README.md
```

## License

MIT. See [LICENSE](LICENSE).
