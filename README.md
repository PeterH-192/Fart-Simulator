# Fart Simulator 3000

The world's most advanced flatulence-based neighborhood demolition simulator, powered by Google Maps.

## Setup

1. Get a Google Maps JavaScript API key from the [Google Cloud Console](https://console.cloud.google.com/apis/credentials)
   - Enable the **Maps JavaScript API** and **Geometry Library**
2. Copy `config.example.js` to `config.js` and paste in your API key
   - `config.js` is gitignored, so your key stays out of version control
3. Open `index.html` in a browser (or serve it locally with `python3 -m http.server`)

## How to Play

1. **Place yourself** - Click the map to drop your green marker
2. **Mark Adam's house** - Click again to place the red target marker
3. **Tune your fart** - Adjust the controls:
   - **Velocity** (1-500 m/s) - How fast the gas travels
   - **Volume** (10-200 dB) - How loud and powerful
   - **Duration** (0.1-10s) - How long you can sustain it
   - **Diet Boost** - Tap a food icon, from Salad (weak) to Nuclear Curry (devastating)
4. **RELEASE THE BEAST** - *Hold* the button to charge up (up to 2.5x power), then let go
5. Watch the blast wave, gas particles, and screen shake — then check the animated **Damage Report**

## Features

- Real Google Maps satellite view of your actual neighborhood
- Geolocation to center the map on your location
- Animated SVG character that puffs its cheeks and tenses while charging
- Hold-to-charge fire button for up to 2.5x extra power
- Canvas particle system: green gas clouds on launch, flying debris on impact
- Animated meters, shimmer bars, and food-icon diet selector
- Live step tracker guiding you through placement and firing
- Expanding blast radius visualization on the map
- Procedurally generated fart sounds via Web Audio API
- Screen shake proportional to blast force
- Animated damage report with a house that visibly crumbles based on damage
- Destruction levels from "No Effect" to "OBLITERATED"

## The Science

The simulation uses highly scientific formulas:

- **Blast Radius** = (velocity * 0.3 + volume * 0.15) * duration * diet_multiplier
- **Force** = velocity * volume * duration * diet_multiplier * 1.5
- **Fart Richter Scale** = log10(force) * 1.2
- Force falls off with inverse-square law from the epicenter

Diet multipliers: Salad (0.5x), Beans (1x), Chili Dog (2x), Mega Burrito (4x), Nuclear Curry (8x)

A house requires ~50,000 N to be destroyed. Good luck!
