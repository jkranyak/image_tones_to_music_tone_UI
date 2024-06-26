# Image Color Palette to Music Converter

This project is an interactive web application that converts the dominant colors of an uploaded image into a unique musical composition. It extracts the main colors from an image and generates a short melody based on these colors.

## Features

- Upload any image file
- Extract dominant colors using K-means clustering
- Convert colors to musical frequencies
- Generate a short musical composition based on the color palette
- Visualize the dominant colors
- Play the generated music directly in the browser

## How it Works

1. **Color Extraction**: The application uses the K-means clustering algorithm to identify the 8 most dominant colors in the uploaded image.

2. **Color to Sound Conversion**: Each extracted color is mapped to a musical frequency. The RGB values of each color are used to calculate a corresponding frequency.

3. **Music Generation**: A short musical piece is generated using the mapped frequencies. The composition uses a pentatonic scale for better harmony and implements a basic rhythmic structure.

4. **Visualization**: The dominant colors are displayed as color swatches, allowing users to see the extracted color palette.

5. **Playback**: The generated music can be played directly in the browser using an audio player.

## Technologies Used

- Python
- Gradio (for the web interface)
- NumPy and Pandas (for data processing)
- Pillow (for image processing)
- scikit-learn (for K-means clustering)
- SciPy (for audio processing)

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/image-to-music-converter.git
   ```

2. Install the required packages:
   ```
   pip install gradio numpy pandas Pillow scikit-learn
   ```

3. Run the application:
   ```
   python app.py
   ```

## Usage

1. Open the application in your web browser.
2. Upload an image using the provided interface.
3. Adjust the duration and tempo sliders if desired.
4. Click the "Submit" button.
5. View the extracted color palette and listen to the generated music.

## Future Improvements

- Implement more advanced music generation algorithms
- Add options for different musical scales and instruments
- Improve the color-to-frequency mapping for more pleasing sounds
- Add the ability to download the generated music as an audio file

## Contributing

Contributions to this project are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
