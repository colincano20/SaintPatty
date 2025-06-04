# Saint Patty

A playful, single-page web app to celebrate St. Patrick's Day. The page asks "Will you be my lucky clover?" and reacts with fun animations depending on your choice.

## Features

- **Interactive question** with **Yes** and **No** buttons.
- Selecting **Yes** triggers a confetti explosion and a friendly message.
- Selecting **No** turns the background red and starts a rain animation.
- **Countdown timer** showing the time remaining until March 17, 2026.
- Pure HTML, CSS, and JavaScript; no build tools or dependencies needed.

## Getting Started

1. Clone this repository or download the source code.
2. Open `index.html` in any modern web browser.
3. Press the **Yes** or **No** button to see the animations in action.

The countdown automatically updates every second.

## Customization

- **Change the countdown date**
  - Edit the line in `index.html` that sets `stPatricksDay` to update the year or time:
  ```javascript
  const stPatricksDay = new Date("March 17, 2025 00:00:00").getTime();
  ```
- **Modify the question or button text** by editing the HTML in `index.html`.
- **Adjust styles** in the `<style>` section of `index.html` to change colors or fonts.

## Credits

Uses the [canvas-confetti](https://cdn.jsdelivr.net/npm/canvas-confetti) library for the celebratory effect when you say "Yes!".

## License

This project is provided for educational and personal use. Feel free to adapt it for your own St. Patrick's Day celebrations!

