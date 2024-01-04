# BLUTIT

## Overview

BLUTIT is a dynamic, user-friendly sandbox environment designed for visualizing map points. It ingeniously integrates the functionality of CodeMirror and Leaflet.js, wrapped in the aesthetically pleasing Nord color scheme. This tool is perfect for anyone looking to effortlessly plot points on a map through a simple yet powerful interface.

## Features

- **CodeMirror Integration**: Utilize the robust features of CodeMirror for a seamless code editing experience.
- **Leaflet.js Mapping**: Leverage the flexibility and performance of Leaflet.js for interactive map displays.
- **Nord Color Scheme**: Enjoy the visually appealing and eye-comforting Nord color scheme, enhancing the overall user experience.
- **Simple JSON Input**: Easily input map points using a structured JSON format with an indent of 4 spaces and no ASCII characters.

## Installation

*Instructions on how to install BLUTIT, including any prerequisites or dependencies.*

```bash
# Example installation steps
git clone [repository-url]
cd blutit
# additional installation steps...
```

## Usage

1. **Prepare Your JSON Data**: Format your data as indent=4, non-ASCII JSON. This will ensure compatibility with the BLUTIT system.
   
   Example JSON:
   ```json
   {
     "points": [
       // Your map points here
     ]
   }
   ```

2. **Input Data into CodeMirror**: Paste your prepared JSON data into the CodeMirror field on the BLUTIT interface.

3. **Visualize on Map**: Upon pasting your JSON data, BLUTIT will automatically plot the points on the integrated Leaflet.js map.

## Contributing

We welcome contributions! If you'd like to contribute, feel free to fork the repository and submit a pull request.

## License

MIT

## Acknowledgments

- CodeMirror: [CodeMirror Website](https://codemirror.net/)
- Leaflet.js: [Leaflet.js Website](https://leafletjs.com/)
- Nord Color Scheme: [Nord Theme](https://www.nordtheme.com/)
