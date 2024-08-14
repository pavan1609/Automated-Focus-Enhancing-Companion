# Focus Buddy: Automated focus enhancing companion

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)
![Platform](https://img.shields.io/badge/platform-Windows-informational.svg)

## Overview

**Focus Enhancer** is a C#-based application designed to help users maintain focus during work sessions by tracking their activity and offering real-time interventions. It monitors active windows, tracks idle time, and captures keyboard input to analyze user engagement. Based on this data, the application can suggest breaks, block distracting websites, or adjust focus goals.

## Features

- **Active Window Tracking**: Monitors and logs the title of the currently active window.
- **Idle Time Detection**: Tracks the amount of time the user is idle.
- **Keystroke Logging**: Captures keyboard input to detect user activity.
- **Custom Interventions**: Suggests breaks or other interventions based on user behavior.
- **Secure Data Handling**: Encrypts user data using AES encryption for security.

## Getting Started

### Prerequisites

- **.NET Framework**: Ensure that the .NET Framework is installed on your machine.
- **Visual Studio** (or any C# IDE): You need a C# development environment to run and modify the code.

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/focus-enhancer.git
    cd focus-enhancer
    ```

2. **Open the project**:
   - Open the project in Visual Studio or your preferred C# IDE.

3. **Restore NuGet packages**:
   - Restore any required NuGet packages that the project depends on.

4. **Build the project**:
   - Build the solution in Visual Studio.

### Usage

1. **Run the application**:
   - Once the project is built, run the application. It will start tracking your activity immediately.

2. **Monitor Activity**:
   - The console will display the active window title, idle time, and captured keystrokes.

3. **Modify Logic**:
   - You can customize the focus-enhancing logic in the `ActivityTracker.cs` file to better suit your needs.

### Files and Directories

- `ActivityTracker.cs`: Main file containing the logic for tracking user activity.
- `encryption.py`: Python script used for AES encryption of user data.
- `frontend/`: Contains the React frontend files for the dashboard.
- `backend/`: Contains the Python backend files for handling encrypted data and storing user activity.

### Roadmap

- **Integration with WebSocket Server**: Real-time updates to the dashboard.
- **Advanced Distraction Analysis**: More sophisticated ML algorithms to detect distractions.
- **Cross-Platform Support**: Extend support to Mac and Linux.
- **User Reports**: Provide detailed weekly/monthly reports to the user.

## Contributing

Contributions are welcome! Please fork this repository, create a new branch for your feature or bugfix, and submit a pull request.

### Steps to Contribute

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-or-bugfix-name
    ```
3. Commit your changes:
    ```bash
    git commit -m "Describe your changes here"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-or-bugfix-name
    ```
5. Open a pull request on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to contact me at [pavanc1609@gmail.com](mailto:pavanc1609@gmail.com).

---

**Focus Enhancer** - Helping you stay focused and productive!
