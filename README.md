# 3D Boxes Background

<p align="justify">✍A web application that displays a 3D boxes background effect. Clicking the button triggers an animation that toggles the view of the boxes.</p>

## Description

<p align="justify">This project creates a visual effect using a 4x4 grid of boxes that form a larger image. When the button is clicked, the boxes expand and contract, creating a 3D effect.</P>

## Features

- 4x4 grid of boxes with a background image.
- Button to toggle the 3D effect.
- Smooth animation for expanding and contracting boxes.

## Usage

To use the 3D Boxes Background:

1. Open the `index.html` file in your web browser.
2. Click the "Click to see Magic 🎩" button to toggle the 3D effect on the boxes.

## Files

- `index.html`: Contains the HTML structure of the application.
- `style.css`: Contains the CSS styles for the application.
- `script.js`: Contains the JavaScript logic for creating the boxes and handling the button click event.
- `README.md`: This file, providing information about the project.

## Dependencies

This project uses Font Awesome for icons, included via CDN:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css" integrity="sha512-1PKOgIY59xJ8Co8+NE6FZ+LOAZKjy+KY8iq0G4B3CyeY6wYHN3yt9PW0XpSriVlkMXe40PTKnXrLnZ9+fkDaog==" crossorigin="anonymous" />
```

### JavaScript Logic
- #### The JavaScript (script.js) is responsible for:

   - Adding event listeners to the button.
   - Toggling the big class on the boxes container to trigger the 3D effect.
   - Creating a 4x4 grid of boxes with the appropriate background positions.

### Key Functions
- createBoxes(): Creates the 4x4 grid of boxes and sets their background positions.
- btn.addEventListener('click', ...): Toggles the big class on the boxes container when the button is clicked.

## License

<p align="justify">This README provides an overview of the project, instructions on how to use it, a description of the files and dependencies, an explanation of the JavaScript logic, and guidelines for contributing and licensing.</p>


## Output Screen

- ##### See the Game
[Click here to see output magic](./Pictures/game.mp4)


