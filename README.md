# Borozdov Tracing

A theme from the Borozdov collection. Two faces — light **Redline**, a white engineering
blueprint, and dark **Floodlight**, the same drawing lit at night. Violet-blue tracing
lines carry every link and rule, one green ping marks the caret and what's done.

![Borozdov Tracing in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/tracing/main/screenshots/light.png)

![Borozdov Tracing in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/tracing/main/screenshots/dark.png)

## Principles

- **A white sheet, ruled in violet-blue.** The canvas is paper white on Redline and a
  deep violet-navy on Floodlight; every link, rule and active state runs on the same
  violet-blue trace — indigo where it has to sit on white and read as text, lighter iris
  where it can glow.
- **One ping.** A single green marks two things only: the blinking caret and a checked
  task. It never appears as running text or as the general accent, so it stays legible
  as a signal, not decoration.
- **Grid paper underneath.** A faint dot grid scrolls with the text in both the reading
  and editing views — the blueprint's own graph paper — and stays out of embeds, popovers
  and canvas cards.
- **A frame the table itself draws.** Tables, callouts and code windows are the same
  hairline-rimmed card at 8–10px corners; no shadows anywhere.
- **Geometric, tracked type.** A geometric sans at 600 for headings that tighten as they
  grow, 400 for body text; eyebrow labels in small tracked capitals, a drafting hand for
  table headers, callout titles and property keys.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts, code blocks and panels drawn as the same hairline-rimmed card
- A scrolling dot grid behind the reading and editing views
- Tags and property pills as ghost outlines that fill with the violet trace on hover
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- A toggle thumb tuned for the violet track, and a checked checkbox in the one green ping
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No embedded fonts, so the theme stays around 13 KB and loads with no flash of unstyled
  text — the platform's own geometric sans carries every size
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory:** Settings → Appearance → Themes → Manage, search for
**Borozdov Tracing**, then **Install and use**.

**By hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/tracing/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Tracing/`, then choose Borozdov Tracing under
Settings → Appearance → Themes.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Redline» — белый инженерный
чертёж, и тёмный «Floodlight» — тот же чертёж под ночным прожектором. Сине-фиолетовые линии
трассировки несут каждую ссылку и правило, один зелёный пинг отмечает курсор и выполненную
задачу. Шрифты не встроены. Устанавливается из каталога: Настройки → Оформление → Темы →
Настроить → Borozdov Tracing → Установить и применить.
