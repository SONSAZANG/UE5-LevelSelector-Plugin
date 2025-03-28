# LevelSelector Plugin Documentation

## Overview
The LevelSelector plugin enhances the Unreal Engine editor workflow by providing a convenient way to select and play different levels directly from the toolbar. This documentation provides detailed information about the plugin's features, installation, and usage.

## Features

### Level Selection Dropdown
- Adds a dropdown menu to the editor toolbar
- Automatically populates with all available levels in your project
- Provides quick access to level selection without navigating through the Content Browser

### Instant Level Play
- One-click level execution from the toolbar
- Streamlines the level testing process
- Reduces time spent on level navigation

## Installation

### Requirements
- Unreal Engine 5.0 or later
- Windows operating system

### Installation Steps
1. Download the plugin from the provided Google Drive link
2. Navigate to your project's Plugins folder
3. Create a new folder named "LevelSelector"
4. Copy all plugin files into the LevelSelector folder
5. Open your project's .uproject file
6. Enable the plugin in Edit > Plugins > Installed > LevelSelector
7. Restart the Unreal Editor

## Usage

### Basic Usage
1. The LevelSelector dropdown will appear in your editor toolbar
2. Select a level from the dropdown menu
3. Click the "Play Level" button to run the selected level

### Advanced Features
- The dropdown automatically updates when new levels are added to your project
- Works with both persistent and non-persistent levels
- Compatible with all Unreal Engine level types

## Technical Details

### File Structure
```
LevelSelector/
├── Source/
│   └── LevelSelector/
│       ├── LevelSelector.h
│       ├── LevelSelector.cpp
│       └── ...
├── Resources/
│   └── Icon128.png
└── README.md
```

### Dependencies
- No external dependencies required
- Built using Unreal Engine's standard plugin architecture

## Troubleshooting

### Common Issues
1. Plugin not appearing in toolbar
   - Ensure the plugin is enabled in Edit > Plugins
   - Restart the Unreal Editor

2. Levels not showing in dropdown
   - Verify that your project contains valid level files
   - Check if the levels are properly saved

### Support
For additional support or bug reports, please refer to the plugin's GitHub repository or contact the developer.

## Version History

### Version 1.0.0
- Initial release
- Basic level selection functionality
- Toolbar integration

## License
This plugin is provided under the MIT License. See the LICENSE file for details. 