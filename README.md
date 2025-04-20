# Nima Art Engine

A powerful NFT art generation engine that allows you to create unique digital art pieces by combining different layers of images.

## Features

- Layer-based art generation
- Customizable output settings
- Preview functionality
- Automatic layer organization
- Desktop output saving
- Cross-platform support (Windows & Mac)

## Installation

### Windows
1. Download the `Nima Art Engine-Setup.exe` installer
2. Run the installer and follow the on-screen instructions
3. Choose your preferred installation directory
4. The application will be installed with all necessary files and a desktop shortcut

## Getting Started

### Setting Up Layers

1. Create a folder structure for your layers:
   ```
   layers/
   ├── Background/
   ├── Body/
   ├── Eyes/
   ├── Mouth/
   └── Accessories/
   ```

2. Place your PNG images in their respective folders
3. Each layer folder should contain images of the same dimensions

### Using the Application

1. **Layer Selection**
   - Click the "Get Folders" button to automatically detect your layer folders
   - The application will scan for layer folders in the default location
   - Each detected layer will appear in the list

2. **Preview**
   - Use the "Preview" button to see how your layers will look when combined
   - Note: The preview may show overlapping attributes, which will be fixed during generation

3. **Generation Settings**
   - **Number of Images**: Enter how many unique combinations you want to generate
   - **Output Format**: Choose between PNG or JPG format
   - **Output Size**: Set the dimensions for your generated images

4. **Generating Art**
   - Click the "Generate" button to start creating your art pieces
   - Generated images will be saved to your desktop
   - Each image will be named with a unique identifier

5. **Layer Management**
   - Use the up/down arrows to reorder layers
   - The order determines how layers are stacked (top to bottom)
   - You can enable/disable specific layers using the checkboxes

## Troubleshooting

- If layers aren't detected, ensure your folder structure matches the required format
- Make sure all images are in PNG format
- Check that images in the same layer have consistent dimensions
- If preview shows overlapping, this is normal and will be fixed during generation
