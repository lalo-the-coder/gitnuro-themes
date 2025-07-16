# GitNuro Themes

A collection of custom themes for [GitNuro](https://github.com/JetpackDuba/Gitnuro), a modern Git GUI client built with Jetbrains Compose and JGit.

## Overview

This repository contains custom themes that can be used to personalize your GitNuro experience. Themes allow you to customize the appearance of the application interface, including colors, fonts, and styling.

## Repository Structure

```
gitnuro-themes/
├── themes/           # Theme files directory
│   ├── dark/        # Dark theme variants
│   ├── light/       # Light theme variants
│   └── custom/      # Custom theme variants
├── docs/            # Documentation and guides
└── README.md        # This file
```

## Available Themes

### Dark Themes

- Coming soon...

### Light Themes

- Coming soon...

### Custom Themes

- Coming soon...

## How to Use

### Installing a Theme

1. Download the theme JSON file you want to use
2. In GitNuro, go to **Settings** → **Appearance** → **Theme**
3. Select **Custom** from the theme dropdown
4. Click **Open File** and browse to your theme JSON file
5. Select the file and GitNuro will apply the custom theme

### Creating Your Own Theme

1. Copy an existing theme file as a starting point
2. Modify the color values and styling properties
3. Save the file with a descriptive name
4. Follow the installation steps above

## Theme File Format

GitNuro themes use a JSON format with the following structure:

```json
{
  "primary": "FF456b00",
  "primaryVariant": "FF456b00",
  "onPrimary": "FFFFFFFFF",
  "secondary": "FF9c27b0",
  "onBackground": "FF141f00",
  "onBackgroundSecondary": "FF595858",
  "error": "FFc93838",
  "onError": "FFFFFFFF",
  "background": "FFe7f2d3",
  "backgroundSelected": "C0cee1f2",
  "surface": "FFc5f078",
  "secondarySurface": "FFedeef2",
  "tertiarySurface": "FFF4F6FA",
  "addFile": "FF32A852",
  "deletedFile": "FFc93838",
  "modifiedFile": "FF0070D8",
  "conflictingFile": "FFFFB638",
  "dialogOverlay": "AA000000",
  "normalScrollbar": "FFCCCCCC",
  "hoverScrollbar": "FF0070D8",
  "diffLineAdded": "FF0070D8",
  "diffLineRemoved": "FF0070D8",
  "isLight": true
}
```

### Color Format

GitNuro uses a specific color format:

- **Format**: `AARRGGBB` (Alpha, Red, Red, Green, Blue)
- **Alpha**: `FF` = fully opaque, `00` = fully transparent
- **Colors**: Hexadecimal values (00-FF for each component)
- **Example**: `FF456b00` = fully opaque green color

### Theme Properties

| Property                | Description                                                 |
| ----------------------- | ----------------------------------------------------------- |
| `primary`               | Primary brand color                                         |
| `primaryVariant`        | Variant of primary color                                    |
| `onPrimary`             | Text color on primary background                            |
| `secondary`             | Secondary brand color                                       |
| `onBackground`          | Text color on background                                    |
| `onBackgroundSecondary` | Secondary text color on background                          |
| `error`                 | Error color                                                 |
| `onError`               | Text color on error background                              |
| `background`            | Main background color                                       |
| `backgroundSelected`    | Background color for selected items                         |
| `surface`               | Surface color                                               |
| `secondarySurface`      | Secondary surface color                                     |
| `tertiarySurface`       | Tertiary surface color                                      |
| `addFile`               | Color for added files                                       |
| `deletedFile`           | Color for deleted files                                     |
| `modifiedFile`          | Color for modified files                                    |
| `conflictingFile`       | Color for conflicting files                                 |
| `dialogOverlay`         | Dialog overlay color                                        |
| `normalScrollbar`       | Normal scrollbar color                                      |
| `hoverScrollbar`        | Hover scrollbar color                                       |
| `diffLineAdded`         | Color for added lines in diff                               |
| `diffLineRemoved`       | Color for removed lines in diff                             |
| `isLight`               | Boolean indicating if theme is light (true) or dark (false) |

## Contributing

We welcome contributions! To add your theme:

1. Fork this repository
2. Create a new theme file in the appropriate directory
3. Add your theme to the list in this README
4. Submit a pull request

### Guidelines for Theme Contributions

- Use descriptive, unique names for your themes
- Include a brief description of the theme's style and inspiration
- Test your theme thoroughly before submitting
- Follow the existing file naming convention
- Include screenshots if possible

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Links

- [GitNuro Repository](https://github.com/JetpackDuba/Gitnuro)
- [GitNuro Documentation](https://github.com/JetpackDuba/Gitnuro#readme)
- [Theme Development Guide](docs/theme-development.md)

## Support

If you have questions about themes or need help creating one:

- Open an issue in this repository
- Check the [GitNuro Discord](https://discord.gg/gitnuro)
- Review the [documentation](docs/)

---

**Note**: This repository is community-maintained and not officially affiliated with the GitNuro project.
