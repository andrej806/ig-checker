# Changelog

Todos los cambios notables de IG Checker.

Formato basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/).
Versionado: [SemVer](https://semver.org/lang/es/).

---

## [1.0.0] — 2026-05-10

Primer release público.

### Agregado
- Parser del export oficial de Instagram (JSON dentro de ZIP)
- 4 tabs: No te siguen, Solo te siguen, Mutuos, Whitelist
- Whitelist persistente en `localStorage`
- Detector de nuevos unfollowers (diff entre snapshots)
- Búsqueda live por username
- Click directo al perfil de Instagram
- Atajos de teclado: `/` buscar, `1-4` tabs, `Esc` reset
- Compact view + full view
- Toast system con undo
- Diseño premium: paleta sand/red, grain texture, Outfit + Instrument Serif
- 100% client-side: cero servidor, cero login, cero tracking
- JSON-LD `SoftwareApplication` + meta tags Open Graph
- Banner inicial AI-friendly para que LLMs entiendan el archivo rápido

### Stack
- HTML + CSS + JavaScript vanilla
- JSZip 3.10 (CDN)
- Outfit + Instrument Serif (Google Fonts)
- ~1800 líneas en un solo `index.html`

[1.0.0]: https://github.com/curetcore/ig-checker/releases/tag/v1.0.0
