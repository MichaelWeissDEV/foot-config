# Foot configuration

Wayland-Terminal mit abgestimmter Schrift, Farben und Zsh.

**[Dokumentation](https://arch-dotfiles.readthedocs.io/en/latest/components/#foot)** ·
[Terminal-Anleitung](https://arch-dotfiles.readthedocs.io/en/latest/terminals/) ·
[Installation und Updates](https://arch-dotfiles.readthedocs.io/en/latest/arch-package/)

```bash
curl -fsSL https://raw.githubusercontent.com/MichaelWeissDEV/dotfiles/main/install.sh | bash -s -- foot
```

Paket: `arch-dotfiles-foot`. Persönliche Einstellungen: `~/.config/foot/foot.ini`.
Dieses eigenständige Repository enthält die Entwicklungsquellen und das Rezept
unter `packaging/arch/PKGBUILD`. Auf `main` pushen; nach erfolgreichem Registry-Build
mit `sudo pacman -Syu` aktualisieren. Details und lokale Builds: [PACKAGING.md](PACKAGING.md).

### Anpassung und Diagnose

Schrift, Farben und Terminalverhalten stehen in `~/.config/foot/foot.ini`. Nach Änderungen ein neues Terminal starten. Die verfügbaren Optionen beschreibt `man foot.ini`.

Eigene Änderungen in der aktivierten Benutzerkopie bleiben bei der Synchronisierung erhalten; neue abweichende Vorgaben erscheinen als `.pacnew`. Siehe [Update und Wiederherstellung](https://arch-dotfiles.readthedocs.io/en/latest/verification/).

[![Package safety](https://github.com/MichaelWeissDEV/foot-config/actions/workflows/package.yml/badge.svg)](https://github.com/MichaelWeissDEV/foot-config/actions/workflows/package.yml)

[MIT-Lizenz](LICENSE).
