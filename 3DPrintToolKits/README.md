# 3DPrintToolKits

A Blender addon that provides tools and utilities for 3D printing workflows.

## Features

- **Sidebar Integration**: Access the addon from the Sidebar in Blender's 3D View (press `N` key)
- **Custom Tab**: All tools are organized under the "3DPrintToolKits" tab
- **Mesh Analysis Tools**: Placeholder buttons for checking thickness and normals
- **Export Settings**: Section prepared for future export functionality

## Installation

1. Download the `3DPrintToolKits` folder
2. Open Blender
3. Go to `Edit` > `Preferences` > `Add-ons`
4. Click `Install...` and select the `__init__.py` file from the `3DPrintToolKits` folder
5. Enable the addon by checking the checkbox next to "3DPrintToolKits"

## Usage

1. Open Blender's 3D View
2. Press `N` key to open the Sidebar
3. Click on the "3DPrintToolKits" tab
4. Use the available tools for your 3D printing workflow

## Requirements

- Blender 3.0 or higher

## Development

This addon is structured to allow easy expansion with additional 3D printing tools and utilities.

### Structure

- `__init__.py`: Main addon file containing:
  - `bl_info`: Addon metadata
  - `VIEW3D_PT_3DPrintToolKits`: Main panel class
  - Registration functions

## License

[Add your license here]

## Author

Your Name

## Version

1.0.0
