# lab4-web-foundations-html
COMP305 Fall 2025 Lab 4 assignment

## Page sections (match the top navigation)
- **About** — glossary terms, inline code, and a tiny **MathML** (Pythagorean) example.
- **Table** — minimal table using `<caption>`, `<colgroup>`, `<thead>`, `<tbody>`, `<tfoot>`.
- **Current Time** — `<time>` auto-updated with a small `<script>` + `<noscript>` fallback.
- **Sleep Tips** — list with edit markup (`<del>`, `<ins>`), `<ruby>` pronunciation, and a `<template>` cloned on button click.
- **Bedtime Routine** — ordered list with `data-*` attributes; JS totals the minutes.
- **Bedtime Log** — preformatted block with `<pre><code>`.
- **Form Demo** — `<form>` with `fieldset/legend`, labeled inputs, `datalist`, `select/optgroup`, `meter`, `progress`, `textarea`, `output`, and buttons.
- **Validation** — before/after images of HTML validation.
- **Media Demos** — `<picture>` + `<img>` with an **image map** (`<map>/<area>`), plus simple video/audio figures.
- **My Sister** — small anchor target for the image map.
- **Contact** — address block with email and phone.

---

## Notable elements used
**Structure:** `header`, `hgroup`, `nav`, `menu`, `main`, `section`, `article`, `aside`, `figure`, `figcaption`, `footer`, `address`, `div`  
**Text/inline:** `abbr`, `cite`, `code`, `data`, `dfn`, `em`, `i`, `kbd`, `mark`, `q`, `ruby`, `rt`, `rp`, `s` (`del`), `small`, `strong`, `sub`, `sup`, `time`, `u`, `var`, `wbr`, `del`, `ins`  
**Media & graphics:** `picture`, `source`, `img (usemap)`, `map`, `area`, `video`, `audio`, `svg`  
**Math:** `math`, `mi`, `mn`, `mo`, `msup`  
**Scripting:** `script`, `noscript`, `template`  
**Forms & widgets:** `form`, `fieldset`, `legend`, `label`, `input` (time/number), `datalist` + `option`, `select` + `optgroup` + `option`, `textarea`, `meter`, `progress`, `output`, `button`, `details`, `summary`, `dialog`

---

## Small behaviors
- **Live clock:** Inline script updates the `<time>` every second. If JS is disabled, `<noscript>` shows a static message.
- **Add tip button:** Clones a `<template>` list item into the Sleep Tips list.
- **Dialog:** Button opens a native `<dialog>`; the inner form’s button closes it.

---

## Validation notes
- Written to pass modern HTML validation
- Video and Audio in not fully implemented just the use of the tags

---

## Credits
- Favicon: flower icon by Freepik via Flaticon (attributed in-page).