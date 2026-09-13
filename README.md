
# Web Dashboard

A personal keyboard-first browser dashboard for organizing frequently used websites into themed collections.

The dashboard is designed as a lightweight, static start page with separate visual environments for different areas such as work, development, entertainment, social platforms, and personal resources.

---

## Screenshots

### Collections

![Collections](Media/collections.png)

### Dashboards

<table>
  <tr>
    <td align="center">
      <strong>Home</strong><br><br>
      <img src="Media/home.png" alt="Home">
    </td>
    <td align="center">
      <strong>Work</strong><br><br>
      <img src="Media/work.png" alt="Work">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Code</strong><br><br>
      <img src="Media/code.png" alt="Code">
    </td>
    <td align="center">
      <strong>Social</strong><br><br>
      <img src="Media/social.png" alt="Social">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Underground</strong><br><br>
      <img src="Media/underground.png" alt="Underground">
    </td>
    <td align="center">
      <strong>Entertainment</strong><br><br>
      <img src="Media/entertainment.png" alt="Entertainment">
    </td>
  </tr>
</table>
---

## Features

- Themed dashboard environments
- Keyboard-first navigation
- Persistent last-dashboard selection
- Direct access to frequently used websites
- Responsive layout
- Lightweight static implementation
- No backend or build system required
- LocalStorage-based dashboard state

---

## Navigation

The dashboard can be navigated primarily using the keyboard.

| Key | Action |
|---|---|
| `h` / `←` | Previous dashboard or item |
| `l` / `→` | Next dashboard or item |
| `Enter` | Open selected item |
| `m` | Open collections |
| `Esc` | Return to collections |

The collections page remembers the last dashboard visited and restores it when opened again.

---

## Project Structure

```text
.
├── collections.html
├── home.html
├── work.html
├── code.html
├── ai.html
├── social.html
├── underground.html
├── entertainment.html
│
├── Reze.jpg
├── hirugama.jpg
├── lightYagami.jpg
├── gintoki.jpg
├── itadori.jpg
├── evaglion.jpg
│
├── README.md
└── LICENSE

