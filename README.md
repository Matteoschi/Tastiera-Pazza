# Tastiera-Pazza
the best of italian world => https://matteoschi.github.io/Tastiera-Pazza/
# Matteo Renzi Reference - Italian Culture Sound Keyboard

## Overview

This project is a simple web-based virtual keyboard that plays sounds inspired by Italian culture when keys are pressed. The keyboard is arranged with buttons representing letters, and clicking any button triggers a corresponding audio clip. The interface is straightforward and minimalistic, designed to provide an engaging and playful way to experience iconic sounds related to Italy, centered around a humorous reference to Matteo Renzi.

## Features

- **Visual Keyboard Layout:** The webpage displays a virtual keyboard with keys arranged in three rows (`sopra`, `medio`, `sotto`) plus special function keys (`ALT` and `SHISH`).
- **Sound Playback:** Each key, when clicked, plays a unique audio clip that represents a sound from Italian culture, adding a cultural and humorous flair to the interaction.
- **Interactive Header:** Clicking the header title also plays an audio clip, enhancing user engagement.
- **Simple and Lightweight:** Built with plain HTML, CSS, and JavaScript, no external dependencies are required, making it fast and easy to deploy.
- **Customizable Sounds:** The audio clips can be easily changed or expanded by modifying the JavaScript code to include new sounds or effects.

## Installation

1. Clone or download this repository.
2. Open the `index.html` file (or your HTML file containing the keyboard) in any modern web browser.
3. Ensure the linked CSS (`tastiera.css`) and JavaScript (`tastiera.js`) files are in the same directory or update the paths accordingly.
4. Make sure all referenced audio files are properly linked and accessible.

## Usage

- Click any key on the virtual keyboard to hear the associated sound.
- Click the title "Matteo Renzi Reference" to play a special audio.
- Use the `ALT` and `SHISH` buttons for additional sound effects.

## Code Structure

- **HTML:** Contains the button elements laid out to form the keyboard.
- **CSS (`tastiera.css`):** Styles the keyboard layout and buttons for a clean user interface.
- **JavaScript (`tastiera.js`):** Defines audio objects and associates play events with each key/button.
- 
![Physics_bullet motion v2 at main · Matteoschi_Physics - Google Chrome 25_01_2023 20_30_04](https://user-images.githubusercontent.com/94646702/214668505-7909ac37-dfce-4000-897b-b9a2d57b48c3.png)
## Example Snippet

```html
<button class="sopra" onclick="audioq.play();">Q</button>
<button class="medio" onclick="audioa.play();">A</button>
<button class="alt" onclick="audioalt.play();">ALT</button>
  



