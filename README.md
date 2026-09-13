# Web Dashboard

A personal keyboard-first browser dashboard for organizing frequently used websites into themed collections.

The dashboard is designed as a lightweight, static start page with separate visual environments for different areas such as work, development, entertainment, social platforms, and personal resources.

---

## Screenshots

### Collections

<!-- Add screenshot here -->

![Collections](Media/collections.png)

### Home

<!-- Add screenshot here -->

![Home](Media/home.png)

### Work

<!-- Add screenshot here -->

![Work](media/work.png)

### Code

<!-- Add screenshot here -->

![Code](media/code.png)

### Social

![Social](media/social.png)

### Underground

<!-- Add screenshot here -->

![Underground](media/underground.png)

### Entertainment

<!-- Add screenshot here -->

![Entertainment](media/entertainment.png)

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
