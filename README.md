# Fart Simulator 3000

The world's most advanced flatulence-based neighborhood demolition simulator, powered by Google Maps.

## Setup

1. Get a Google Maps JavaScript API key from the [Google Cloud Console](https://console.cloud.google.com/apis/credentials)
   - Enable the **Maps JavaScript API** and **Geometry Library**
2. Open `index.html` and replace `YOUR_API_KEY_HERE` with your actual API key
3. Open `index.html` in a browser

## How to Play

1. **Place yourself** - Click the map to drop your green marker
2. **Mark Adam's house** - Click again to place the red target marker
3. **Tune your fart** - Adjust the sliders:
   - **Velocity** (1-500 m/s) - How fast the gas travels
   - **Volume** (10-200 dB) - How loud and powerful
   - **Duration** (0.1-10s) - How long you can sustain it
   - **Diet Boost** - From Salad (weak) to Nuclear Curry (devastating)
4. **RELEASE THE BEAST** - Hit the button and watch the blast wave propagate across the map
5. Check the **Damage Report** to see if Adam's house survived

## Features

- Real Google Maps satellite view of your actual neighborhood
- Geolocation to center the map on your location
- Expanding blast radius visualization
- Fart Richter Scale readings
- Procedurally generated fart sounds via Web Audio API
- Screen shake proportional to blast force
- Destruction levels from "No Effect" to "OBLITERATED"

## The Science

The simulation uses highly scientific formulas:

- **Blast Radius** = (velocity * 0.3 + volume * 0.15) * duration * diet_multiplier
- **Force** = velocity * volume * duration * diet_multiplier * 1.5
- **Fart Richter Scale** = log10(force) * 1.2
- Force falls off with inverse-square law from the epicenter

Diet multipliers: Salad (0.5x), Beans (1x), Chili Dog (2x), Mega Burrito (4x), Nuclear Curry (8x)

A house requires ~50,000 N to be destroyed. Good luck!
