# Apps and tools outside the Brewfile

Keep these alongside the Homebrew and Mac App Store entries in [Brewfile](Brewfile). This is a reinstall checklist, not an installer.

Last checked on this Mac: 29 October 2026. "Installed" means the app or command was found; it does not confirm sign-in, licensing, or permissions. Homebrew availability has not been checked for every item below. If an item gains a verified Brewfile entry, move it there.

## Desktop apps found in Applications

| App | Reinstall method / notes |
| --- | --- |
| Antigravity | Official developer download |
| CodexBar | Official developer release |
| Compositor | Official developer download |
| FluidVoice | Official developer download |
| Hermes | Desktop app; official developer release |
| Obsidian Web Clipper | Mac App Store / Safari extension; separate from Obsidian |
| OpenCodex | Official developer release; separate from ChatGPT |
| Pica | Official developer download |
| RAWmakase | Official developer download |
| Redlamp | Official developer download |
| Telegram | Official developer download or Mac App Store |
| Things 3 | Mac App Store; use the owning Apple Account |
| Tinycast | Official developer release |
| macshot | Official developer download |

These apps were present in /Applications on the date above. Exact download links and App Store IDs still need verification before automating installation.

## Command-line tools found

- Claude Code: `claude` in `~/.local/bin`.
- Hermes: `hermes`, `hermes-acp`, and `hermes-agent` in `~/.local/bin`.

Use the projects' official setup instructions when reinstalling. Do not store passwords, API keys, or account tokens in this repository.

## Setup after installing

- Enable Safari extensions in Safari settings as wanted.
- Grant OpenLogi Agent Accessibility and Input Monitoring permissions when prompted to enable mouse controls.
- Sign in and restore licenses only where required.
- Do not reinstall Logitech Options+ alongside OpenLogi; OpenLogi replaced it.

## Existing install requests

The Brewfile records additional desired apps, not just apps currently installed. Preserve those entries when updating this checklist.
