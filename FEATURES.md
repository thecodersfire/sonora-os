# Built-in features for sonora-os

Purpose: music production

1. **prepare a creative project** — run sonora-os-workspace. It creates ~/Documents/sonora-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run sonora-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/sonora-os-session-plans/.
3. **check project and export readiness** — run sonora-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/sonora-os-workspace features/sonora-os-plan features/sonora-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for music production:

1. **Ardour** — org.ardour.Ardour
2. **OBS Studio** — com.obsproject.Studio
3. **VLC** — org.videolan.VLC

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for music production:

1. **Kdenlive** — edit video timelines (org.kde.kdenlive)
2. **Blender** — create 3D assets and animations (org.blender.Blender)
3. **GNOME Sound Recorder** — capture voice and field notes (org.gnome.SoundRecorder)
4. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
5. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
6. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
7. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
8. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
9. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)
10. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
