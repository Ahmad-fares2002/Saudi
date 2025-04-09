# AR Football Stadium App

Welcome to the AR Football Stadium App! This app provides an immersive experience for football fans, guiding them through the stadium using augmented reality. By scanning your ticket, you can access the AR features that will help you find your seat and explore the stadium.

## Requirements

- Xcode (For iOS builds)
- An iOS device (IPhone) for testing the AR experience
- Apple laptop
- A ticket (attached in this repository) to scan in the app

## Setup Instructions

1. **Download the Repository:**
   - Clone or download this repository to your local machine.

2. **Ticket Scanning:**
   - Please **attach the ticket** file included in the GitHub repository. The ticket will be used to start the app's AR experience. Make sure the ticket is available for scanning when you run the app.

3. **Building and Running the iOS App:**

   - Navigate to the `Build/` folder.
   - Inside the `Build/` folder, you will find the exported iOS project from Unity. Open this folder in Xcode.
   - Open the `.xcodeproj` file with Xcode.
   - Connect your iOS device to your computer.
   - In Xcode, select your device as the target and click on the **Run** button.
     - Ensure that your development team is selected in the **Signing & Capabilities** tab under the Xcode project settings for a smooth build process.
     - Wait for Xcode to build and deploy the app to your iOS device.

4. **UI/UX Experience:**
   - Once the app is launched on your device, you'll be presented with a simple and user-friendly UI.
   - Select the **"Inside" experience** to begin the AR journey.
   - Follow the on-screen instructions and refer to the provided video for a detailed walkthrough on how to interact with the app.
   - The app will guide you through the various AR features, such as locating your seat and exploring stadium facilities.

5. **Testing the AR Features:**
   - Hold your ticket in front of your device's camera to begin scanning.
   - The app will recognize the ticket and activate the relevant AR experience based on its contents.
   - Once the AR view is active, you'll be able to navigate through the app, view key information about the stadium, and follow the guides to your destination.

## Notes

- Make sure your iOS device supports AR (ARKit is required).
- If you encounter any issues, please check that the ticket is properly visible in the camera view and try again.
- The UI is designed to be intuitive. If you need further help, follow the instructions in the video provided in the repository.
- You need Apple laptop to run the experince
- Make sure that the ticket image is clearly visible and properly aligned in the camera view.

## Troubleshooting
- **AR features are not working**: Ensure that your device supports ARKit and has the necessary permissions to use the camera.
