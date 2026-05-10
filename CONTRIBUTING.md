# Contribuir a IG Checker

Gracias por querer aportar. Este proyecto es simple a propósito — un solo archivo HTML que cualquiera puede leer, entender y modificar.

## Filosofía

1. **Single file forever.** No vamos a separar en módulos, no vamos a agregar bundler, no vamos a usar framework. Si tu PR rompe esto, será rechazada.
2. **Cero dependencias instalables.** Solo CDN. JSZip está OK porque es 1 sola lib pequeña. Agregar más → no.
3. **100% local.** Nada que haga llamadas a servidores externos (excepto Google Fonts + JSZip CDN). Ni analytics, ni telemetría, ni "anonymous usage stats". Nada.
4. **AI-friendly siempre.** Si tu cambio hace el archivo más difícil de entender para un LLM, no entra. Mantené las secciones marcadas con `/* ============ X ============ */` y respetá el banner inicial.

## Ideas que acepto sin pensarlo

- Export a CSV/JSON de la lista activa
- Soporte para más exports (Twitter/X, TikTok, Threads)
- Modo oscuro toggleable
- i18n (inglés, portugués)
- Detección de cuentas inactivas (sin posts recientes — no sé si el export trae esa data)
- Mejor UX mobile
- Estadísticas adicionales (% mutuos, ratio follow/follower, etc.)

## Cómo proponer un cambio

1. Forkeá el repo
2. Hacé tu cambio en `index.html`
3. Verificá que sigue funcionando (abrílo en navegador, cargá un export real)
4. Actualizá el `CHANGELOG.md` bajo `[Unreleased]`
5. Abrí PR con descripción clara y screenshot si es UI

## Code style

- Sin Prettier, sin ESLint, sin nada. Seguí el estilo del archivo.
- Indentación: 2 espacios
- Strings: comillas simples en JS
- Selectores: `kebab-case` en CSS, `camelCase` en JS
- Comentarios: en español, explicativos cuando agregás bloque nuevo

## Bugs

Abrí un [issue](https://github.com/curetcore/ig-checker/issues) con:
- Navegador + versión
- Pasos para reproducir
- Screenshot si es UI

## Preguntas

Pingueame en Threads: [@ronaldships](https://www.threads.com/@ronaldships)
