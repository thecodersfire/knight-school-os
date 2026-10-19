# Built-in features for knight-school-os

Purpose: chess study

1. **prepare study and research files** — run knight-school-os-workspace. It creates ~/Documents/knight-school-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run knight-school-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/knight-school-os-session-plans/.
3. **check study and source readiness** — run knight-school-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/knight-school-os-workspace features/knight-school-os-plan features/knight-school-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for chess study:

1. **Zotero** — org.zotero.Zotero
2. **Anki** — net.ankiweb.Anki
3. **Foliate** — com.github.johnfactotum.Foliate

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
