# NFT Art Generation Engine (NFT-AGE)

A simple tool to create unique NFT artwork by combining different image layers.

## 1. Download and Installation

First, download the app from:  
https://github.com/NimaZaeim/Nima-s-NFT-Art-Engine/releases/tag/v1.10

### For Windows:
1. Download `Nima Art Engine-Setup.exe`
2. Double-click the downloaded file to run the installer
3. Follow the installation steps (just keep clicking "Next")
4. The app will install with a desktop shortcut

## 2. Configuration Settings

When you first open the app, you'll see the Configuration tab with these important settings:

- **Supply**: Enter how many NFT images you want to create (example: 5)
- **Name**: Your collection name (example: "Nima NFT Arts")
- **Symbol**: A short code for your collection (example: "NZ")
- **Description**: What your collection is about
- **Width** and **Height**: Set your image size (example: 1080x1080 pixels)

## 3. Setting the Output Path

1. Click the "Output Path" button
2. Choose where you want your finished NFTs to be saved
3. Select any folder on your computer

## 4. Loading Your Layers
Tip: The app comes with sample layers to help you get started. Just click "Get Folders" to load them!

1. Go to the "Layers Order" tab
2. Click "Get Folders" - the app will automatically find your layer folders
3. Your layers will appear in a list
4. Use the up/down arrows to change the layer order (top layers cover bottom ones)
5. You can turn layers on/off using the checkboxes

## 5. Creating Your NFTs

1. Go to the "Create" tab
3. Click "Generate" to start creating
4. Wait while the app combines your layers in unique ways
5. When finished, your NFTs will be in your chosen output folder

## Troubleshooting

- All images in a layer folder should be the same size
- Use PNG format for best results
- The preview might look messy, but your final NFTs will be perfect
- Try different layer orders for new looks
- If you want to add your own layer folders, make sure to follow the structure below:
   ```
   layers/
   ├── Background/
   ├── Body/
   ├── Eyes/
   ├── Mouth/
   └── Accessories/
   ```
