# WinColor

WinColor is a Python program designed to adjust and customize color profiles for displays on Windows. The goal is to achieve optimal color accuracy and reduce eye strain by tweaking display settings and font smoothing configurations.

## Features

- Apply custom color profiles for displays.
- Adjust font smoothing settings to enhance text readability.
- Configuration through a simple JSON file.

## Requirements

- Python 3.x
- Windows operating system

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/wincolor.git
   ```

2. Navigate to the project directory:

   ```bash
   cd wincolor
   ```

3. Ensure you have Python installed on your system.

## Configuration

Create a configuration file named `wincolor_config.json` in the project directory with the following structure:

```json
{
    "font_smoothing": true,
    "contrast": 1200,
    "orientation": 1,
    "smoothing_type": 2,
    "color_profiles": [
        "sRGB Color Space Profile.icm",
        "Adobe RGB (1998).icm"
    ]
}
```

- `font_smoothing`: Enable or disable font smoothing.
- `contrast`: Set the contrast level for font smoothing.
- `orientation`: Set the orientation for font smoothing.
- `smoothing_type`: Set the type of smoothing.
- `color_profiles`: List of color profiles to apply.

## Usage

Run the program using Python:

```bash
python wincolor.py
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Disclaimer

This program makes changes to system settings. Use it at your own risk. Ensure you have backups of your current settings before applying any changes.