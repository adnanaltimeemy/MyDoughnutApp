
# MyDoughnut

**Live well. Spend wisely. Protect the planet.**

A personal Doughnut Economics tracker for iPhone and iPad. Each week it shows whether your daily choices meet your own needs without overshooting the planet's limits.

![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20iPadOS%2017%2B-1F6B5A)
![Privacy](https://img.shields.io/badge/privacy-Data%20Not%20Collected-9BE15D)

[User Guide (PDF)](MyDoughnut%20User%20Guide.pdf) · [Privacy Policy](privacy.html)

---

## Contents

* [About](#about)
* [Features](#features)
* [How scoring works](#how-scoring-works)
* [Premium](#premium)
* [Privacy](#privacy)
* [In this repository](#in-this-repository)
* [Acknowledgements](#acknowledgements)
* [License](#license)

---

## About

Most lifestyle apps track one thing: money, calories, steps. **MyDoughnut** brings wellbeing, personal finance, sustainability and community together in one visual dashboard. It's based on Kate Raworth's *Doughnut Economics*, which pictures a **safe and just space** between two boundaries:

* **The social foundation** (inner ring): what you need to live well.
* **The ecological ceiling** (outer ring): what the planet can sustain.

MyDoughnut scores **12 areas** over the last 7 days. If you fall short on a need, a red wedge grows **inward**; if you overshoot a planet limit, it grows **outward**. Staying in the green ring is the goal.

| Life Needs (inner ring) | Planet Impact (outer ring) |
| :--- | :--- |
| Physical health | Carbon footprint |
| Mental wellbeing | Energy usage |
| Education | Transport |
| Income | Waste |
| Housing | Water |
| Community | Sustainable purchases |

---

## Features

| Feature | Description |
| :--- | :--- |
| **Doughnut dashboard** | A live, interactive doughnut chart with shortfall and overshoot wedges. Tap any segment for details |
| **Daily check-in** | Rate any of the 12 areas from 1 to 5 (5 is always best), or **Skip** areas that don't apply. Takes about a minute |
| **Life Needs and Planet Impact pages** | Per-ring summary, score chart with targets, area list, tips and related challenges |
| **Habits** | Daily habits linked to areas, a 7-day date strip, streaks and haptics |
| **Weekly challenges** | 14 challenges; 4 are featured each week, rotating every Monday |
| **Impact Budget** | Money and estimated $\text{CO}_2\text{e}$ side by side, sustainable share of spend, carbon by category |
| **Levels and badges** | XP, 8 levels from *Seedling* to *Ecosystem*, and 9 badges that are kept permanently |
| **Trends** | Week-by-week balance, Life Needs and Planet Impact (last 4 weeks free) |
| **Widgets** | Home Screen (small/medium/large), Lock Screen (circular/rectangular/inline), and an **interactive Today's Habits** widget |
| **Reminders** | Daily check-in (skipped once you've checked in), streak-at-risk and challenge last-call notifications |
| **Apple Health** | Optional, read-only: steps, exercise, sleep, mindful minutes, walking and cycling distance |

For step-by-step instructions, see the [User Guide (PDF)](MyDoughnut%20User%20Guide.pdf).

---

## How scoring works

Each area gets a score from **0 to 100**, where higher is always better. It's **in balance** when it reaches its target: 50 by default, or a personal goal with Premium.

| Input | Contribution |
| :--- | :--- |
| **Check-in rating** | $1 \rightarrow 0$, $2 \rightarrow 25$, $3 \rightarrow 50$, $4 \rightarrow 75$, $5 \rightarrow 100$ (averaged over rated days) |
| **Purchases** | Sustainable share of spend sets *Sustainable purchases*. Estimated $\text{CO}_2\text{e}$ against your weekly carbon budget feeds *Carbon footprint* |
| **Apple Health** | Steps and exercise feed *Physical health*. Sleep feeds *Mental wellbeing* ($+$ up to $10$ for mindful minutes). Walking and cycling add up to $+15$ to *Transport* |
| **Habits** | $+3$ per completion, up to $+15$ per area |
| **Challenges** | $+10$ per completed challenge, up to $+20$ per area |

The inputs are averaged, the bonuses added, and the result kept between 0 and 100. The User Guide has a worked example.

> Carbon figures are rough spend-based estimates to help you compare choices, not an exact footprint.

---

## Premium

**£4.99 per month, with a 1-week free trial.**

* **Trends** over 12 weeks, 6 months and 1 year.
* **Monthly best and worst** area.
* **Personal goals:** your own target for every area, plus step, exercise, sleep and active-travel goals. Applied everywhere, including widgets.

Subscriptions are handled by Apple and can be managed or cancelled in iOS **Settings $\rightarrow$ [your name] $\rightarrow$ Subscriptions**.

---

## Privacy

MyDoughnut is private by design. **Everything stays on your device.**

* No accounts, no servers, no analytics, no advertising, no tracking.
* Apple Health is **read-only**, used only for scoring, never shared, never used for ads, and never stored in iCloud by the app.
* Subscriptions are handled entirely by Apple.
* App Store privacy label: **Data Not Collected**.

Full policy: [privacy.html](privacy.html).

---

## In this repository

| File | What it is |
| :--- | :--- |
| `README.md` | This overview |
| `MyDoughnut User Guide.pdf` | The full user guide |
| `privacy.html` | The privacy policy |
| `AppIcon_2.png` | The MyDoughnut app icon |

---

## Acknowledgements

* **Doughnut Economics** by Kate Raworth, the framework that inspired the app's concept and visual.

MyDoughnut is an independent app. It is not affiliated with, or endorsed by, Kate Raworth or Doughnut Economics Action Lab (DEAL).

---

## License

Copyright © 2026 **Adnan Altimeemy**. All rights reserved.
