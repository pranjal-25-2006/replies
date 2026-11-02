# Free Claude Skills pack: video editor + 3D motion designer

Checked on 2026-11-03. Everything here is free and open source. Numbers (stars, installs) change daily.
A "skill" is a folder of instructions that teaches Claude Code how to do a job. These three make Claude a video editor and a motion designer.

## Before you start (5 minutes)
- Install **Node.js 22 or newer** and **FFmpeg** (HyperFrames' stated requirements).
- Use **Claude Code** (the skills install into it).
- Safety: a skill can make Claude run commands on your computer. Read a skill's SKILL.md before you install it, and only install from sources you trust.

---

## 1. HyperFrames: the video editor skill
**What it does:** you describe a video, Claude writes it as HTML, and HyperFrames renders it to an MP4 on your computer. Titles, captions, charts, explainers, vertical reels.
**Proof it's real:** 77,000+ GitHub stars, Apache-2.0 licence, README says "no per-render fees or commercial-use thresholds".
**Install:**
```
npx skills add heygen-com/hyperframes
```
Skills inside: hyperframes, hyperframes-cli, hyperframes-registry, media-use, figma, remotion-to-hyperframes, reverse-any-video, slideshow.
**Free vs paid:** rendering locally is free. The README also mentions hosted/cloud options, HyperFrames Pro (for reverse-any-video) and that media-use can work with HeyGen. Skip those to stay 100% free.
**First prompts to try:**
1. "Use the hyperframes skill to make a 9:16, 10 second title card for [my shop name] with a dark background and one animated headline. Render it locally to an MP4."
2. "Make a 15 second vertical reel from these 3 bullet points: [paste]. Add word-by-word captions."
3. "Turn this chart data into an animated bar chart video: [paste numbers]."

## 2. three.js skills: the 3D skill
**What it does:** gives Claude current, correct knowledge of three.js (the web's 3D engine): geometry, materials, lighting, textures, animation, shaders, post-processing, loading 3D models, and React Three Fiber.
**Proof it's real:** MIT licence, 3,900+ GitHub stars, 13 skills, targets three.js r186.
**Install:**
```
npx skills add cloudai-x/threejs-skills
```
**First prompts to try:**
1. "Use the threejs skills to build a single HTML page with a glossy 3D logo cube that slowly rotates, with soft lighting. I should be able to open it in my browser."
2. "Add a post-processing bloom glow and a shader background to that scene."
3. "Make the camera fly around the object in a 10 second loop."
Tip: combine with HyperFrames to turn a 3D scene into a video.

## 3. Motion graphics skills: the motion designer pack
**What it does:** 15 skills for launch-grade motion graphics written as code: launch videos, Apple-style launch films, animated charts, milestone reveals, 3D title sequences, loop covers, Reels export.
**Proof it's real:** MIT licence, 529 GitHub stars. Its README says "Nothing here needs an API key". It uses HyperFrames to export MP4.
**Install:**
```
npx skills add charlie947/motion-graphics-skills
```
**How to start:** run the `brand-intake` skill first. It writes brand.md and MOTION.md so every video matches your brand.
**First prompts to try:**
1. "Run brand-intake for [my business]. Then use title-sequence-3d to make a 6 second 3D title sequence for the name."
2. "Use animated-chart to show our monthly sales: [paste numbers]."
3. "Use reel-export to export the result as a vertical 1080x1920 MP4."

---

## Honorable mention: Remotion skills
`npx skills add remotion-dev/skills` (13 skills, 730K installs for the main one). Remotion makes videos with React. It is free for individuals, for-profit companies with up to 3 employees, and non-profits; larger companies need a paid company licence. Check remotion.dev/docs/license.

## Honest notes
- Claude Code itself runs on your own Claude plan; these skills are free add-ons.
- Skills do not replace taste: give Claude a clear brief, look at the frames, and ask for fixes.
- Star counts and install counts were read on 2026-11-03.

Made by @aipranjal. Reel sources: github.com/heygen-com/hyperframes, github.com/cloudai-x/threejs-skills, github.com/charlie947/motion-graphics-skills.
