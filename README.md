# Web4 Web2App - Android Template

This repository provides a simple way to convert Web4 networks into an Android WebView app. Use this template to deploy your Web4 network in a fully functional mobile app.

## Installation

### 1. Clone the Repository
Clone the repository to your local directory:
```bash
git clone https://github.com/Web4-Organisation/Web4-Web2App.git
cd Web4-Web2App
```

### 2. Customize URL and App Name
Edit the file `app/src/main/res/values/strings.xml` to configure the app name and URL of your Web4 network:
```xml
<resources>
    <string name="app_name">Web4</string>
    <string name="web_url">https://linkspreed.club</string>
</resources>
```
Replace the `web_url` value with the URL of your Web4 network and customize the `app_name` to fit your branding.

### 3. Build the APK
Once you've made the adjustments, build the APK using Gradle:
```bash
./gradlew assembleDebug
```

The APK will be created in the `app/build/outputs/apk/debug/` directory.

## Notes

- **WebView App**: This template uses WebView to load your Web4 network, ensuring a seamless experience for your users.
