# Simple AR Model Viewer

A web-based AR application that allows users to view a 3D model by scanning a marker or QR code. When users click on the 3D model, they are shown product information.

## Features

- Works on both iOS and Android mobile devices
- Simple AR experience using the device camera
- Displays a 3D GLB model in augmented reality
- Interactive: clicking the model shows product information
- Everything in a single page for simplicity
- Built-in QR code and marker for easy sharing

## Setup and Deployment

### Local Development

1. Install Node.js if you don't have it already
2. Clone this repository
3. Install dependencies:
   ```
   npm install
   ```
4. Start the development server:
   ```
   npm run dev
   ```
5. Open the URL shown in your terminal

### Deploying to Vercel

1. Install Vercel CLI:
   ```
   npm install -g vercel
   ```
2. Deploy to Vercel:
   ```
   vercel
   ```
3. Follow the prompts to complete the deployment

## Usage

1. When you open the app, you'll see two options:
   - QR Code: Share this with others to access the AR experience
   - AR Marker: Use this as a reference marker for the AR experience
2. Click "Start AR" to begin the experience
3. Allow camera access when prompted
4. Point your camera at the marker displayed in the app (or print it using the link provided)
5. The 3D model will appear above the marker
6. Tap on the 3D model to see product information

## Technical Details

- Built with A-Frame and AR.js for web-based augmented reality
- Uses QRCode.js for QR code generation
- The 3D model is a GLB file loaded into the scene
- Compatible with most modern mobile browsers that support camera access

## Customizing

- Replace `stand-1.glb` with your own GLB model
- Edit the product information section in `index.html`
- Adjust the model positioning, scale, and rotation as needed

## License

MIT 