<div align="center">

# ✈ flight timer

*a relaxing exam timer for the projector*

[![theme](https://img.shields.io/badge/catppuccin-mocha-cba6f7?style=flat-square&labelColor=11111b&color=cba6f7)](https://github.com/catppuccin/catppuccin)
[![no install](https://img.shields.io/badge/no_install-just_open-a6e3a1?style=flat-square&labelColor=11111b)](index.html)
[![single file](https://img.shields.io/badge/single-html_file-89b4fa?style=flat-square&labelColor=11111b)](index.html)

</div>

---

<table>
<tr>
<td><img src="screenshots/dawn.png" alt="dawn — plane climbing through a peach sunrise"/></td>
<td><img src="screenshots/midday.png" alt="midday — bright blue sky, plane at the peak"/></td>
<td><img src="screenshots/dusk.png" alt="dusk — golden-mauve sunset, plane descending"/></td>
</tr>
<tr>
<td align="center"><sub>dawn</sub></td>
<td align="center"><sub>midday</sub></td>
<td align="center"><sub>dusk</sub></td>
</tr>
</table>

---

A plane takes off, arcs through a full day of sky, and lands exactly when time runs out. Set a duration, hit **Begin Flight**, and let your students watch the clock — without watching the clock.

<br>

## ☀️ the sky tells the time

The sky, light, and plane position all move together in real time.

| progress | scene |
|:---:|---|
| `0%` | deep night — stars out, engine idling on the setup screen |
| takeoff | sunrise blooms as the plane climbs from the left |
| `50%` | bright midday blue at the peak of the arc |
| descent | golden hour as the plane begins to drop |
| `100%` | darkness falls — *time's up · pens down* |

<br>

## 🚀 getting started

Double-click `index.html` — no installation, no internet, no server required.

> **Projector tip:** go fullscreen with `F11` on Windows/Linux or `⌘ Ctrl F` on Mac for the full effect.

<br>

## 🎛️ controls

| input | action |
|---|---|
| presets or `hr / min / sec` inputs | set the duration |
| **Begin Flight** | launches the timer |
| `Escape` | reset at any time |
| `[` &nbsp;/&nbsp; `]` | −5 min / +5 min while running |
| `−10m` `−5m` `+5m` `+10m` | on-screen buttons in the bottom corners |

<br>

## 🖥️ reading the hud

```
Landing · 2:45 pm                          3:22 pm
                       1:23:45
                   time remaining
                  ends at 2:45 pm
−10m  −5m                              +5m  +10m
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

The landing time lives in the top-left so students always know the end time at a glance.

<br>

---

<div align="center">
<sub>built with 🩷 and <a href="https://github.com/catppuccin/catppuccin">catppuccin mocha</a></sub>
</div>
