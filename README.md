# Gemini Desktop App 🚀

This is an unofficial Gemini desktop application built with Electron. It provides a convenient way to access and use Google Gemini on your desktop.
It is a fork from https://github.com/Alyetama/Gemini-Desktop

I forked this project due to security concerns. I reviewed the code to ensure that my Google login credentials are not sent to any third-party service or otherwise misused. This fork gives me full control over the code I run.
## Features ✨

- Access the full functionality of Google Gemini.
- Native desktop experience with window controls and menus.
- Persistent sessions (you stay logged in).
- Optimized for performance and usability.

## Authentication
You cannot use Passkey for login on that app. Just use the password authentication.


## Screenshots 📸

![Screenshot1](assets/screenshot_1.png)
![Screenshot2](assets/screenshot_2.png)

## Installation 📥

1. **Download the latest release:**
   - **macOS (arm64):** [Download](https://github.com/siegfriedbolz/Gemini-Desktop/releases/download/1.0/Gemini.Desktop-1.0.0-arm64.dmg)

2. **Install the app:**
   - **macOS:** Open the `.dmg` file and drag the app to your Applications folder.

## Development 🛠️

1. **Install dependencies:**

   ```bash
   npm install
   ```

2. **Start the development server:**

   ```bash
   npm start
   ```

## Building 🏗️

To build the app for different platforms, use the following command:

```bash
npm run dist
```

This will create an installer for macOS (`.dmg`) in the `dist` directory.

## Contributing 🤝

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License 📜

This project is licensed under the [MIT License](https://opensource.org/license/mit).
