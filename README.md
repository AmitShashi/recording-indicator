# Recording Indicator
Recording indicator for obs or other similar apps

since app like this dont exist on internet thats why i created it so please consider following me as part of my payment. Thank You

______________________________________________________________________________________________
# Recording Indicator App

**Versions Included:** v2 (Image-Based Indicator) and v9 (No Image Required Indicator)

## Introduction

The **Recording Indicator** app is designed to display a visual indicator on your screen when you start or stop recording or streaming. It works with any recording software like OBS, Bandicam, etc., and is particularly useful for gamers and content creators who need a non-intrusive way to know when they're live or recording.

## Features

- **v2 (Image-Based Indicator):**
  - Use custom images as indicators.
  - Supports transparent PNG images.
- **v9 (No Image Required Indicator):**
  - Create hollow circle indicators without needing image files.
  - Customize circle size and color for each function.

## Prerequisites

- **Operating System:** Windows 10 or Windows 11
- **Python Version:** 3.6 or higher
- **Python Packages:**
  - `Pillow` (for image handling)
  - `keyboard` (for global hotkey support)

## Installation

1. **Install Python:**
   - Download and install from [python.org](https://www.python.org/downloads/).
   - Add Python to your system PATH during installation.

2. **Install Required Packages:**
   - Open Command Prompt or PowerShell.
   - Run:
     ```bash
     pip install pillow keyboard
     ```

3. **Download the App:**
   - Clone or download the repository.
   - Extract the `recording indicator.zip` file.

## Usage

### Version 2 (v2) - Image-Based Indicator

1. Navigate to the `v2` folder.
2. Prepare your indicator images (transparent PNG files).
3. Run `main.py`.
4. Configure key bindings and upload images.
5. Select indicator position.
6. Click "Start App" to begin.
7. Press your configured keys to display indicators.

### Version 9 (v9) - No Image Required Indicator

1. Navigate to the `v9` folder.
2. Run `main.py`.
3. Configure key bindings and select colors.
4. Set circle size (1-50 pixels).
5. Select indicator position.
6. Click "Start App" to begin.
7. Press your configured keys to display indicators.

## Troubleshooting

- **Indicator Not Showing:**
  - Ensure correct key bindings.
  - Run the app as administrator if necessary.
- **Overlay Captured in Recording:**
  - Adjust recording software settings to avoid capturing the overlay.
  - Use game capture mode instead of display capture in OBS.

## Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Created with ❤️ by **Amit Shashi**
