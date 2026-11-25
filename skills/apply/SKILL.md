---
name: apply
description: Build or restyle a UI in a requested visual style. Use for requests like "구글 풍으로 만들어줘", "애플 느낌으로 바꿔줘", or "make this Stripe-inspired".
---

Find the requested style document in `../../design-md/`, resolved relative to the folder containing this `SKILL.md`, not the project's working directory. Each available style is stored at `<style>/DESIGN.md` (for example, `apple/DESIGN.md` or `stripe/DESIGN.md`).

Match the requested brand or style to an available folder, including translated names such as "애플" for `apple`. Read the matching `DESIGN.md` and use its colors, typography, spacing, components, and layout rules to guide the UI implementation or restyling. Preserve the project's existing framework and requested functionality.

If no matching style document exists, say so and ask which available style to use or whether to proceed with a general interpretation. Do not claim that an unavailable style has a bundled reference.
