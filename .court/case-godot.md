Make game assets (a PS1/PSX-style graphics toolkit for Godot 4 called "RetroForge") and sell them in the Godot store, to raise money for AI subscriptions and other expenses.

Facts given by the user:
- The user is a Korean high school senior (2026), planning to study physics at university. Not a professional developer; no development experience at the start.
- Goal: raise money for AI subscription fees and other expenses by making and selling things. Profit comes first.
- Budget: up to 500,000 KRW may be spent. Target profit: 1,000,000 KRW.
- Period: from now (2026-10-16) through the winter break until university entrance.
- The user applies through early admission (susi), so exams do not affect their schedule, and they can invest many hours per week.
- The user says a collaboration environment exists in which Claude, Codex and Gemini work together and review each other.
- The user's main device is an Android tablet and they work through the web (claude.ai/code).
- The user wants to sell assets in "the Godot store".
- A previous trial of a broader "build and deploy games and websites for money" idea ended GUILTY 6-0 because no product, sales channel, revenue basis, weekly hour cap or payout route for a minor was named. The user has since said exams do not limit their hours. The user's age, guardian consent and payout route are NOT yet stated.

The full plan written with GPT is in the file .court/RetroForge_plan_from_GPT.md. Read it. Its main content:
- Product: RetroForge, a Godot 4.x addon with pixelation, color quantization/dither, vertex snap/PSX material, distance fog, 3 style presets (Subtle Retro, PSX Horror, Bright Low-Poly), a before/after demo, install docs. Free Lite plus Pro at a test price of $7.99-$12.99, reference $9.99.
- Competitors listed in the plan (public prices at time of lookup): PSX - Godot Shader (free / pay what you want), PSX Look ($5.99), Godot 4 Shader Pack ($4.99), Retro Horror FX Toolkit ($4.99). The plan lists their pages on itch.io.
- The plan has a 14-day schedule, gates for validation, and success measures of 10 conversations with potential users, 30 Lite downloads, 5 install-success feedbacks and 3 expressions of willingness to pay. It states there is no evidence yet of paid demand.
- The plan assigns work to Claude Code (orchestrator), Codex (implementation) and Gemini (review) and uses GitHub issues, PRs and CI.

The user said that GPT was not told the details of this environment, so these statements in the plan are unverified or may conflict with the real setup (listed as facts, not opinions):
1. The plan says the main development environment is "Android tablet + Termux (optional) + GitHub + a connectable remote dev environment". In reality the work runs in a cloud Linux container opened from the claude.ai/code web app on the tablet. The tablet is used as a browser client.
2. The plan assumes Codex and Gemini can be called as agents. In the current session no Codex or Gemini tool is visible; the user says a setup exists but its connection is not confirmed.
3. The plan sells on itch.io-style listings and compares itch.io prices, while the user says the sales channel is "the Godot store". Which store, its rules, fees, whether paid items are allowed, and payout and age conditions are not verified in the record.
4. The Godot engine is not installed in the cloud container (checked: no `godot` command). Whether a headless export, GPU rendering, WebGL or Android testing can run there is not verified. The plan's tests need real devices and browsers.
5. The plan's prices are in USD; the user's budget and target are in KRW.
6. The plan's schedule is 14 days; the user's period is about 19 weeks. The plan's student-time limits were written before the user said exams do not matter.
7. The plan's final section says to follow rules such as no spending, publishing, account creation or external sending without user approval, and to confirm minors' payout eligibility with a guardian.
