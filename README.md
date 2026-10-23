# Conduct Chaos!

**A browser-based railway dispatch and operations game**  
*A [0] creation · 2026*

Conduct Chaos! puts you in charge of a busy three-line railway network. Direct passenger and freight trains to their assigned terminals, operate track switches, manage traffic, and respond to equipment failures before small problems become major disruptions.

What starts as a relaxed introduction gradually becomes a test of timing, situational awareness, and operational decision-making.

## Features

- **Five campaign levels**, each with its own delivery target and increasingly demanding traffic.
- **Nine interactive switches** across three color-coded railway lines.
- **Live train routing** with red, blue, and green destination terminals.
- **Passenger and freight trains**, each with an assigned destination and individual train number.
- **Emergency train holds** to manage congestion and potential conflicts.
- **Track wear, switch jams, and equipment failures** that require attention.
- **Two reusable repair crews** and a limited-use **emergency track kit**.
- **Endless Dispatch**, unlocked after completing the campaign, with adaptive difficulty and saved personal records.
- A clean, light-themed interface with no music or sound effects.

## How to play

The goal is to deliver trains to their **matching colored terminals** without exhausting the network's integrity.

1. Select **Start shift** to begin.
2. Check the **Next inbound train** panel for the incoming train's origin, destination, and arrival countdown.
3. With **Route tracks** selected, click a circular track switch to cycle through the available directions: straight, up, or down. Switches at the outer edges only offer valid routes.
4. Click a moving train to **hold** it temporarily; click it again to **release** it. A stopped train still occupies the track, so other trains can collide with it.
5. If a switch becomes damaged or jammed, select **Repair crew** or **Track kit**, then click the affected switch.
6. Deliver enough trains to reach the level target. Between levels, the simulation stops until you choose **Start shift** again.

### Dispatch tools

| Tool | What it does | Availability |
| --- | --- | --- |
| **Route tracks** | Changes the outgoing direction of a healthy switch. | Unlimited use. |
| **Repair crew** | Repairs a worn or jammed switch in about four seconds of active gameplay. | Two crews can work simultaneously; crews are reusable. |
| **Track kit** | Instantly repairs a damaged or jammed switch. | One kit per campaign level; replenished every 25 deliveries in Endless Mode. |

Repairs **do not cost credits**. The challenge is managing repair time and crew availability, and deciding when an emergency kit is worth using.

### Mistakes and scoring

- A **correct delivery** increases your arrival count and dispatch score. Consecutive successful deliveries earn additional points.
- A **wrong terminal** costs one network-integrity point.
- A **train collision** costs two network-integrity points.
- A shift ends when network integrity is depleted.

You begin each campaign level with **four integrity points**.

## Campaign levels

| Level | Location | Successful deliveries required | Challenge |
| --- | --- | ---: | --- |
| **1** | North Yard Operations | **10** | Slow trains and spaced-out arrivals for learning the controls. |
| **2** | Freight Interchange | **17** | Faster trains, irregular arrivals, and occasional equipment faults. |
| **3** | Metropolitan Junction | **25** | Heavier overlapping traffic and more frequent faults. |
| **4** | Central Signal District | **25** | Tighter traffic spacing and greater pressure on repair management. |
| **5** | Grand Terminal Rush | **25** | The most demanding campaign traffic and switch-failure conditions. |

The successful-delivery count **resets at the start of each level**, while the campaign score carries forward. Every completed level allows an **unlimited break**: the next one does not start until you click **Start shift**.

## Endless Dispatch

Finish Level 5 to unlock **Endless Dispatch**, a separate mode with no fixed delivery target.

- Difficulty increases every **eight successful deliveries**.
- Train speed, traffic frequency, and operational pressure increase progressively.
- Difficulty levels off at **pressure tier 9**, rather than increasing indefinitely.
- An emergency track kit becomes available again every **25 deliveries**.
- Best Endless scores and delivery records are saved in the browser.

## Play the game

### On a computer

Download the game's `.html` file and open it in a modern desktop browser. The game is self-contained, so there are **no packages to install, accounts to create, or external game assets to download**.

### On GitHub Pages

If you want other people to play directly from a web link:

1. Rename the latest game file to **`index.html`**.
2. Upload `index.html` and this `README.md` to the **root of your GitHub repository**.
3. In your repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then select your main branch and **`/(root)`**, and save.
5. When publishing finishes, open the website link shown in the Pages settings. You can share that link with players.

GitHub's official instructions: [Creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).

### On iPhone or another phone

Use the **hosted GitHub Pages link** in a mobile browser. The iPhone Files app may show a preview of an HTML file without running the game. On smaller screens, the railway map can be scrolled horizontally to reach the full network. Mobile usability is still an area for refinement.

## How the game is built

- **HTML5** — interface structure
- **CSS** — responsive layout and visual design
- **JavaScript** — train movement, switch controls, collisions, repairs, levels, and scoring
- **Canvas API** — railway map and animated train graphics
- **Browser local storage** — records and Endless Mode unlock

The game is designed to run from a **single HTML file**. Records are stored locally in the browser and are not automatically synchronized between devices or browsers.

## Project direction

Conduct Chaos! is built around one central idea: **complexity should come from managing the railway, not navigating the interface**. The design emphasizes clear controls, understandable warnings, gradual difficulty progression, and short, repeatable gameplay sessions.

Possible future improvements include further touchscreen optimization, expanded visual customization, and additional accessibility refinements.

## Creator and attribution

**Conduct Chaos! — A [0] creation · 2026**

The `[0]` creator mark also appears within the game's interface and HTML metadata. The custom switch-track symbol was supplied by the creator.

## Usage and licensing

This repository is intended to showcase Conduct Chaos! and make the game available to play. **No open-source license is included with this README.** Public visibility on GitHub should not be interpreted as permission to redistribute or rebrand the project. For requests to reuse the artwork, branding, or game materials, contact the project creator.
