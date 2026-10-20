VOYDWOLF CREW — COMMAND DECK v1
================================
Prepared for https://github.com/Jamesw212/jamesw212.github.io

GITHUB WEB EDITOR INSTRUCTIONS
1. In your repository, use branch menu (currently main) > View all branches > New branch. Name it voydwolf-redesign and base it on main. Choose that branch before editing.
2. Add new root file voyd-theme.css, copying the entire file from this package.
3. Replace the existing root index.html with index.html from this package.
4. Replace live.html with live.html from this package.
5. Replace latest.html with latest.html from this package.
6. Leave style.css, script.js, images/, neon_clock.html, and other files UNCHANGED.
7. In titles.html, directly after its style.css link, add:
   <link rel="stylesheet" href="voyd-theme.css">
   Optional: change visible Jamesw212 Gaming / Tools branding to VoydWolf Crew. Its generated text will still say Jamesw212 until script.js is updated separately.
8. For a preview, note that GitHub Pages normally publishes main only. Opening a branch file in GitHub does NOT preview a live webpage. Create a pull request for review, and merge to main only when ready to publish, or configure a separate Pages preview environment.

This release intentionally keeps the original script.js to preserve the stream title generator, and keeps existing Twitch/YouTube account links and IDs. It does NOT add an actual live detection system. 'Open' describes community access, not stream live status. The rotating navigation rings are CSS-based. The provisional V symbol is not your final wolf logo.

If publishing a custom domain later, Twitch embeds' parent= hostname MUST be updated.
