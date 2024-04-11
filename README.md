# Video Player Documentation

## Overview

This documentation provides an overview of the functional video player integration into a web interface. The player is equipped with basic controls including play, pause, mute, volume toggle, and full-screen mode. The implementation uses JavaScript, HTML, and CSS, leveraging the Playable JavaScript library.

[Check site demo](https://barseeek.github.io/videoplayer/)
## Features

- Play/Pause: Allows users to play or pause video content.
- Mute/Unmute: Provides the ability to mute or unmute the video volume.
- Fullscreen Mode: Offers a fullscreen viewing option for enhanced viewing.
  
## Setup

### Prerequisites

- A modern web browser compatible with HTML5, CSS3, and JavaScript.
- Access to the internet to load resources from a CDN.
- Python3 (optional for livereload)

### Installation

Clone the repository or download the files to your local machine:

```bash
git clone https://github.com/barseeek/videoplayer.git
```

### Usage

1. Embedding in Web Pages:

   Include the HTML and JavaScript setup in your web page:

   ```html
      <!DOCTYPE html>
      <html lang="en">
      <head>
        <meta charset="UTF-8">
        <title>Video Player</title>
        <link rel="stylesheet" href="static/font-awesome.min.css">
        <link rel="stylesheet" href="static/style.css">
      </head>
      <body>
        <div id="player" class="player">...</div>
        <script src="static/player.js"></script>
        <script>
          createPlayer({elementId: 'player'});
        </script>
      </body>
      </html>
   ```
   Make sure all paths are correctly set up for CSS and JavaScript files based on your project structure.

2. Use python and livereload (optional):
   ```bash
   pip install livereload
   livereload path_to_directory
   ```

### Customization

Modify the styles in static/style.css to customize the appearance of the player according to your branding requirements.

## Debugging

Check the console in your web browser for any errors or warnings that might indicate problems with the player setup. Ensure all files are loaded correctly by verifying the network tab in browser's developer tools.

## Support

For further assistance, refer to the Playable documentation