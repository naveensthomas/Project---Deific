# 🪐 OUTPOST ZERO: The Last Colony

**An interactive space colony survival simulator that teaches STEM.**

Built by **Team Deific** for the **NASA Space Apps Challenge 2026**.

> *Your planet. Your rules. Your survival.*
> One colony. Limited resources. A hundred days to prove humanity can survive beyond Earth.

---

## 🚀 Play the game

- **Live demo:** `[add your GitHub Pages or hosted link here]`
- **Project demo slides:** `[add your public slide deck link here]`

No installation, accounts or build tools needed. The game runs in any modern browser on desktop, tablet and mobile.

---

## 📖 About the project

Students become a mission commander and must keep a Mars or Moon colony alive for **100 days**. Every decision changes oxygen, water, food, power, radiation and the structure of the habitat, so the science behind space survival becomes something players can feel and test.

This is a playable simulation, not a static educational page.

## ✨ Features

| Feature | What it does |
|---|---|
| **Two missions** | Mars (dust storms, thin air, radiation, limited sunlight) or the Moon (lunar night, no atmosphere, micrometeorites, heavy radiation) |
| **Colony command center** | Live gauges for oxygen, water, food, power, crew health, radiation, hull integrity and materials |
| **Colony building** | 9 buildings you can place on a map, upgrade to level 3, or remove for a partial refund |
| **Engineering trade-offs** | Every building shows its advantages and disadvantages before you build it |
| **Random emergencies** | 11 events (solar storm, oxygen failure, leaks, contamination, meteorites and more), each with several responses and visible costs |
| **Science learning** | A short science explanation appears for buildings and after every emergency |
| **Technology tree** | 7 research upgrades with measurable gameplay effects |
| **Mission advisor** | Rule-based hints that explain *why* something is a problem, without making decisions for you |
| **What-If simulator** | Change solar output, population, recycling efficiency or shielding and see a 30-day projection graph |
| **Five stages** | First Landing, Survival Systems, Expansion, Crisis Management, Permanent Settlement |
| **Scoring and achievements** | Six achievements and a score based on survival, decisions, research and learning |
| **Failure analysis** | If the colony fails, the report explains the cause and what to do differently |
| **Mission journal** | A timeline of builds, upgrades, emergencies and achievements |
| **Challenge code** | Copy a code to compare scores with friends |
| **Auto-save** | Progress is saved in the browser with `localStorage` |

## 🎮 How to play

1. Choose **Mars** or the **Moon**.
2. Select a building in the **Build** tab, then tap an empty tile on the map.
3. Keep power generation above demand. Every building uses electricity.
4. Keep oxygen, water and food above zero, and radiation below 70.
5. Press **END DAY** or **5 DAYS**. When an emergency appears, read the costs and choose.
6. Research technology, check the **Advisor** and **What-If** tabs, and survive until Day 100.

## 🔬 Science concepts covered

- **Electrolysis**: splitting water into hydrogen and oxygen
- **Hydroponics**: growing plants without soil
- **Thin atmosphere**: why Mars has so little air
- **Radiation**: how particles damage human cells and how shielding helps
- **Solar power**: how photovoltaic cells turn light into electricity
- **Water recycling**: why closed loops are essential in space

## 🛠️ Tech stack

- HTML, CSS and vanilla JavaScript in a single file
- Canvas API for the animated star field
- `localStorage` for saving progress
- Google Fonts (Orbitron) for typography

The simulation logic is organised into separate parts inside the script: building data, event library, technology tree, the daily `tick()` resource engine, scoring, and rendering.

## 💻 Run locally

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

Then open `index.html` in your browser. No server or dependencies are required.

> If your file is named `outpost-zero.html`, rename it to `index.html` so GitHub Pages can serve it.

## 🌐 Deploy with GitHub Pages

1. Upload `index.html` and this `README.md` to your repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. After a minute your game is live at `https://<your-username>.github.io/<your-repo>/`.

## 📁 Project structure

```text
.
├── index.html    # The complete game (UI, styles and simulation logic)
└── README.md     # This file
```

## 🧪 Game balance at a glance

- Start: Living Habitat, Oxygen Generator and 2 Solar Stations, with 160 materials
- Crew starts at 4 and a new member arrives every 20 days, so you need more habitats
- Radiation above 70 damages crew health
- The colony fails if crew health or hull integrity reaches zero
- Win by surviving all 100 days

## 👥 Team Deific

| Name | Role |
|---|---|
| `[Member 1]` | `[Role]` |
| `[Member 2]` | `[Role]` |
| `[Member 3]` | `[Role]` |

## 🔮 Future ideas

- Online leaderboard for the multiplayer challenge
- More events, buildings and map sizes
- 3D colony view with Three.js
- Optional AI-powered advisor using an API
- Teacher mode with classroom score tracking

## 🙏 Acknowledgements

- NASA Space Apps Challenge
- Science concepts simplified for school students

## 📄 License

`[Choose a license, for example MIT, and add a LICENSE file]`
