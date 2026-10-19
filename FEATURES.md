# Built-in features for sonora-os

Purpose: music production

1. **prepare a creative project** — run sonora-os-workspace. It creates ~/Documents/sonora-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run sonora-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/sonora-os-session-plans/.
3. **check project and export readiness** — run sonora-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/sonora-os-workspace features/sonora-os-plan features/sonora-os-check "$HOME/.local/bin/"
