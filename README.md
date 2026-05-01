# 000-Flutter-App 📱: Navigation Drawer & Asset Showcase

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/teto06920623/000-Flutter-App/flutter.yml?branch=main&style=for-the-badge)](https://github.com/teto06920623/000-Flutter-App/actions/workflows/flutter.yml)

A foundational Flutter application meticulously crafted to demonstrate the implementation of a robust Navigation Drawer with a custom `UserAccountsDrawerHeader`, seamlessly integrating local assets for a personalized user experience. This project serves as an excellent starting point for developers looking to incorporate essential UI navigation patterns and asset management in their Flutter applications.

## 📸 Application Screenshots

<table>
  <tr>
    <td style="border: none;"><img src="https://github.com/user-attachments/assets/650c8529-a084-4f15-96ea-3032b926c853" width="300" alt="App Screenshot 1: Main screen with AppBar and 'Welcome!' message." /></td>
    <td style="border: none; font-size: 50px; color: gray; vertical-align: middle;">|</td>
    <td style="border: none;"><img src="https://github.com/user-attachments/assets/807d18d7-bac2-4ac2-a365-63bfa40afa29" width="300" alt="App Screenshot 2: Navigation Drawer open, showing UserAccountsDrawerHeader and menu items." /></td>
  </tr>
</table>

## ✨ Key Features

This application showcases the following core UI components and functionalities:

*   **Custom AppBar:** A aesthetically pleasing blue AppBar with a centered title and crisp white icons, ensuring brand consistency.
*   **Sophisticated Navigation Drawer:**
    *   **UserAccountsDrawerHeader:** A fully customized header displaying a user profile picture (loaded from local assets), username, and email, providing a personalized touch.
    *   **ListTiles:** Well-organized navigation items, each accompanied by a distinct leading icon (e.g., Profile, Course, Settings, etc.), facilitating intuitive navigation.
*   **Dynamic Body Content:** A central "Welcome!" message, elegantly styled to demonstrate basic text rendering and layout.
*   **Seamless Asset Integration:** Proper configuration and loading of local image assets (e.g., `profile-pic.png`) via `pubspec.yaml`, ensuring efficient resource management.

## 🚀 Technologies Used

*   **Flutter:** The powerful UI toolkit for building natively compiled applications for mobile, web, and desktop from a single codebase.
*   **Dart:** The client-optimized language for fast apps on any platform.

## 🛠️ Installation & Setup

Follow these steps to get a local copy of the project up and running on your machine.

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/teto06920623/000-Flutter-App
    cd 000-Flutter-App
    ```

2.  **Install Dependencies:**
    ```bash
    flutter pub get
    ```

3.  **Asset Configuration:**
    Ensure your `pubspec.yaml` file correctly specifies the assets directory. This project uses the `Photos/` folder for images.
    ```yaml
    flutter:
      uses-material-design: true
      assets:
        - Photos/
    ```

4.  **Run the Application:**
    Connect a device or start an emulator, then execute:
    ```bash
    flutter run
    ```
    The application should launch, displaying the main screen with the custom AppBar and "Welcome!" message.

## 📖 Usage

*   **Open the Drawer:** Tap the hamburger icon (menu icon) in the top-left corner of the AppBar to open the navigation drawer.
*   **Explore Drawer Items:** Interact with the `ListTile` items in the drawer to observe their visual feedback (though they do not navigate to different screens in this basic demo).
*   **View User Header:** Observe the `UserAccountsDrawerHeader` displaying the profile picture, name, and email loaded from assets.

## 📂 Project Structure

The repository adheres to a clean and standard Flutter project structure:

```
000-Flutter-App/
├── lib/
│   └── main.dart             # Main application entry point and UI logic
├── Photos/
│   └── profile-pic.png       # Local image assets
├── pubspec.yaml              # Project dependencies and asset declarations
├── README.md                 # Project documentation
└── ...                       # Other Flutter-generated files
```

## 🤝 Contributing

Contributions are always welcome! If you have suggestions for improvements or new features, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeature`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature/YourFeature`).
6.  Open a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## 📞 Contact & Author

Connect with me for collaborations, questions, or just to say hello!

*   **Author:** Taha Mohamad
*   **GitHub:** [@teto06920623](https://github.com/teto06920623)
*   **Email:** teto06920623@gmail.com
*   **LinkedIn:** [Taha Mohamad Alrefaey](https://www.linkedin.com/taha-mohamad-alrefaey-a32bb538b)
*   **Phone/WhatsApp:** +01037392403