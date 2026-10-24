<div align="center">

<img src=".github/media/banner.png" alt="plantism" width="100%">

<br>
<br>

<a href="https://github.com/pvrzz/plantism/stargazers"><img src="https://img.shields.io/github/stars/pvrzz/plantism?style=for-the-badge&logo=github&logoColor=1c2614&label=stars&labelColor=fdfd94&color=83c46c" alt="stars"></a>
<a href="https://github.com/pvrzz/plantism/network/members"><img src="https://img.shields.io/github/forks/pvrzz/plantism?style=for-the-badge&logo=github&logoColor=1c2614&label=forks&labelColor=fdfd94&color=83c46c" alt="forks"></a>
<a href="https://github.com/pvrzz/plantism/commits/main"><img src="https://img.shields.io/github/last-commit/pvrzz/plantism?style=for-the-badge&logoColor=1c2614&label=last%20watered&labelColor=fdfd94&color=83c46c" alt="last commit"></a>
<img src="https://img.shields.io/badge/version-2.2.0-ff89be?style=for-the-badge&labelColor=fdfd94" alt="version">

<br>

<img src="https://img.shields.io/badge/Equicord-supported-83c46c?style=flat-square&labelColor=1c2614" alt="Equicord">
<img src="https://img.shields.io/badge/Vencord-supported-83c46c?style=flat-square&labelColor=1c2614" alt="Vencord">
<img src="https://img.shields.io/badge/BetterDiscord-supported-83c46c?style=flat-square&labelColor=1c2614" alt="BetterDiscord">
<img src="https://img.shields.io/badge/dark%20%2B%20light-both%20bloom-dcff5c?style=flat-square&labelColor=1c2614" alt="dark and light">

<br>
<br>

**a storybook garden for your discord.**<br>
hand-drawn flowers, hanging vines, fireflies at night and pollen in the sun.

<br>

[**install**](#-plant-it) · [**two moods**](#-two-moods) · [**features**](#-whats-growing) · [**customize**](#-tend-your-garden) · [**the garden**](#-the-garden)

</div>

<br>

## 🌙 two moods

plantism follows whatever mode discord is in. every color in the theme is tuned twice, once for each.

<table>
<tr>
<td width="50%" align="center"><b>🌙 night garden</b><br><sub>dark mode</sub></td>
<td width="50%" align="center"><b>☀️ sunlit meadow</b><br><sub>light mode</sub></td>
</tr>
<tr>
<td><img src=".github/media/preview-dark.png" alt="plantism dark mode"></td>
<td><img src=".github/media/preview-light.png" alt="plantism light mode"></td>
</tr>
<tr>
<td align="center"><sub>deep forest greens, butter-yellow headings, drifting fireflies</sub></td>
<td align="center"><sub>parchment chat, sage sidebars, deep fern headings, pollen sparkles</sub></td>
</tr>
</table>

<br>

## 🌱 plant it

<details open>
<summary><b>Equicord / Vencord</b> (recommended)</summary>
<br>

**online theme** (updates on its own)

1. open **Settings → Themes → Online Themes**
2. paste this link and save:

```
https://raw.githubusercontent.com/pvrzz/plantism/main/plantism.theme.css
```

**local file**

1. download [`plantism.theme.css`](https://raw.githubusercontent.com/pvrzz/plantism/main/plantism.theme.css)
2. **Settings → Themes → Open Themes Folder**, drop it in
3. flip plantism on

</details>

<details>
<summary><b>BetterDiscord</b></summary>
<br>

1. download [`plantism.theme.css`](https://raw.githubusercontent.com/pvrzz/plantism/main/plantism.theme.css)
2. **Settings → Themes → Open Themes Folder**, drop it in
3. flip plantism on

</details>

<br>

## ✨ what's growing

<table>
<tr>
<td width="50%" valign="top">

**🎨 look + feel**
- two full palettes, auto-switching with discord's mode
- **650+ plant icons** replacing discord's own, glossy and ink-outlined with little sprouts, color-coded (pink for danger, butter for stars + gifts, lime for checks)
- chunky cartoon buttons that press in when clicked
- butter-yellow tooltips, petal-pink mentions + badges
- paper grain texture instead of flat colors
- server icons bloom into petals on hover
- no blurple left anywhere it can reach

</td>
<td width="50%" valign="top">

**🌼 the garden**
- a vine canopy hanging over the chat
- ferns, daisies, mushrooms + a butterfly in the corner
- grass and flowers growing over your user panel
- vines climbing the server list + member list
- a swaying daisy on every server banner
- fireflies (dark) and pollen (light) drifting by
- sprouts next to every category

</td>
</tr>
<tr>
<td valign="top">

**🔤 type**
- **Fraunces** for headers, server names + sections
- **Quicksand** for channels, buttons + ui
- **Nunito** for messages

</td>
<td valign="top">

**🖥️ fits every window**
- ultrawide down to snapped half-windows
- decorations scale down or tuck away when space is tight
- respects reduced motion + your chat font size

</td>
</tr>
</table>

<br>

## 🪴 tend your garden

drop any of these into **QuickCSS** (or the top of the theme) to make it yours.

```css
:root
{
    --plant-section-case: uppercase;
    --plant-corner-size: 320px;
    --plant-chat-corner: none;
    --plant-chat-garland: none;
    --plant-panel-grass: none;
    --plant-rail-vine: none;
    --plant-members-vine: none;
    --plant-header-daisy: none;
}
```

| variable | what it does | default |
| :-- | :-- | :-- |
| `--plant-section-case` | casing for category + section titles | `none` |
| `--plant-corner-size` | size of the corner garden in chat | `260px` |
| `--plant-chat-corner` | the corner garden (`none` hides it) | ferns + flowers |
| `--plant-chat-garland` | the vine canopy over chat | garland |
| `--plant-panel-grass` | grass over the user panel | grass |
| `--plant-rail-vine` | vine behind server icons | vine |
| `--plant-members-vine` | vine along the member list | soft vine |
| `--plant-header-daisy` | swaying daisy on server banners | daisy |
| `--plant-category-bullet` | sprout next to categories | sprout |
| `--plant-moss` `--plant-lime` `--plant-butter` `--plant-petal` | the core palette | 🌿 |

<details>
<summary><b>tune the moods</b></summary>
<br>

each mode has its own set of `--p-*` colors. override them inside `.theme-dark` or `.theme-light`:

```css
.theme-dark
{
    --p-chat: #2a4226;
    --p-garden-opacity: 0.7;
    --p-fireflies: 0.5;
}

.theme-light
{
    --p-chat: #fbfcef;
    --p-fireflies: 0;
}
```

</details>

<br>

## 🌸 the garden

every piece is hand-drawn with the same ink outline. PNGs live in [`assets/`](assets), SVG sources in [`assets/src/`](assets/src).

<div align="center">
<table>
<tr>
<td align="center"><img src="assets/daisy.png" width="64"><br><sub>daisy</sub></td>
<td align="center"><img src="assets/bloom.png" width="64"><br><sub>bloom</sub></td>
<td align="center"><img src="assets/leaf.png" width="64"><br><sub>leaf</sub></td>
<td align="center"><img src="assets/sprout.png" width="48"><br><sub>sprout</sub></td>
<td align="center"><img src="assets/vine.png" width="30"><br><sub>vine</sub></td>
</tr>
<tr>
<td align="center" colspan="2"><img src="assets/grass.png" width="200"><br><sub>grass</sub></td>
<td align="center" colspan="3"><img src="assets/garland.png" width="260"><br><sub>garland</sub></td>
</tr>
<tr>
<td align="center" colspan="5"><img src="assets/corner.png" width="260"><br><sub>corner garden</sub></td>
</tr>
</table>
</div>

<br>

## 📈 growth

<div align="center">
<a href="https://star-history.com/#pvrzz/plantism&Date">
<img src="https://api.star-history.com/svg?repos=pvrzz/plantism&type=Date" alt="star history" width="80%">
</a>
</div>

<br>

## 🐛 found a weed?

discord renames its classes a lot, so a spot can slip back to default colors after an update. [open an issue](https://github.com/pvrzz/plantism/issues) with a screenshot and where it happened, and it gets pulled.

<br>

<div align="center">

<img src=".github/media/logo.png" width="96" alt="plantism logo">

**grown by [pvrz](https://pvrz.lol)**<br>
<sub>if plantism made your discord a little greener, leave a ⭐</sub>

</div>
