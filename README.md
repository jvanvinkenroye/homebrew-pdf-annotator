# Homebrew PDF Annotator (deprecated)

> **⚠️ Dieser Tap ist eingestellt.** Die Formel ist bei v0.4.1 stehengeblieben
> und wird nicht mehr aktualisiert. Bitte stattdessen via
> [uv](https://docs.astral.sh/uv/) installieren:
>
> ```bash
> uv tool install git+https://github.com/jvanvinkenroye/pdfAnnotater.git
> pdf-annotator
> ```

Homebrew tap for [PDF Annotator](https://github.com/jvanvinkenroye/pdfAnnotater).

## Migration von Homebrew zu uv

```bash
brew uninstall pdf-annotator
brew untap jvanvinkenroye/pdf-annotator
uv tool install git+https://github.com/jvanvinkenroye/pdfAnnotater.git
```

Die Daten bleiben erhalten — sie liegen unabhängig von der Installationsart
in `~/Library/Application Support/PDF-Annotator/`.
