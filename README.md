# Ionic + Angular App: Multi-Image Share to Social & Cloud

This is a cross-platform mobile app built with **Ionic 5** and **Angular 9**, designed to let users select multiple images from their device and share them seamlessly via social media apps (e.g., WhatsApp, Instagram), email attachments (Gmail), cloud drives (Google Drive), or any other compatible sharing platforms.

## Key Features

- Select **multiple images** from device storage
- Share images to:
  - Social Media (WhatsApp, Facebook, Instagram, etc.)
  - Email clients (e.g., Gmail attachment)
  - Cloud storage (Google Drive, OneDrive, etc.)
  - Any app that supports Android/iOS sharing
- Preview and remove images before sharing
- Integration with Cordova plugins

## Technologies Used

- **Angular 9**
- **Ionic 5**
- **Bootstrap**
- **Cordova Plugins**

# How Sharing Works
- User selects multiple images from their device gallery
- The app stores temporary copies using the Filesystem plugin
- Upon clicking "Share", the app invokes the native share sheet
- User selects a target app (social media, Gmail, Drive, etc.)
- Images are passed as file attachments via URI or base64

## Installation

```bash
git clone https://github.com/your-repo/your_repo.git
cd your_repo
npm install

# Run in browser
ionic serve
```

# Run on Android/iOS (add platforms first if needed)
- ionic cordova run android
- ionic cordova run ios
- ionic build --prod


# Dependencies
- Angular 9
- Ionic 5
- Bootstrap 4
- Cordova Plugins (Camera, File, Social Sharing, etc.)
- REST API backend


## Copyright

© Banti Shaw. All rights reserved.

- This is a personal project. Redistribution, copying, modification, or commercial use of this project or any part of its code without explicit permission from the author is strictly prohibited.


## License

This project is licensed under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)** license.

- Under the following terms:
- **Attribution** — You must give appropriate credit.
- **NonCommercial** — You may not use the material for commercial purposes.
- **NoDerivatives** — If you remix, transform, or build upon the material, you may not distribute the modified material.

### Summary
This is a **personal project**. Do not copy, redistribute, or modify the code for commercial or public use without written permission from the author.

Full license text: [https://creativecommons.org/licenses/by-nc-nd/4.0/](https://creativecommons.org/licenses/by-nc-nd/4.0/)

