# Immediate Shutdown Button

![image](https://github.com/user-attachments/assets/18cbcbbc-2993-4543-9034-4f2c34e086c5)


## Description

This is a simple project that includes a one-time button to turn off the computer immediately. The goal of this button is to solve the problem of slow computers that have difficulty shutting down through the "Start" menu, which may take a long time to appear.

Sometimes, users need to shut down their computers quickly, but the slow performance of the device delays the appearance of the necessary windows. For this reason, I designed a button that, when clicked, shuts down the computer immediately. 

**Important Note**: Since the program shuts down the computer immediately upon running, you must **manually pin it to the taskbar before running it**. This ensures easy access for future use.

This solution helps simplify the shutdown process for users who face slow devices, saving time and effort.

## Tools Used

- **PowerShell**: For writing the script.
- **Win-PS2EXE**: To convert the script from `.ps1` to an executable `.exe` file.

## How to Use

1. Download the executable file from [Here](https://github.com/aiotv1/Immediate_Shutdown_Button/raw/refs/heads/main/shutdown.exe) .
2. **Manually pin the program to the taskbar** before running it:
   - Right-click the `ShutdownButton.exe` file.
   - Select **"Pin to taskbar"**.
3. Once pinned, you can click the button in the taskbar to shut down the computer immediately.

**Warning**: Do not double-click the program directly without pinning it to the taskbar first, as it will shut down your computer immediately.

## Video Tutorial

For a step-by-step visual guide, check out this video tutorial:

[video Link](https://youtu.be/qEMoOITTbgY)

## Installation

If you want to modify the script or convert it to an executable file yourself, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/aiotv1/Immediate_Shutdown_Button.git
    ```
2. Navigate to the folder:
   ```bash
   cd immediate-shutdown-button
   ```
3. Run the script using PowerShell:
   ```powershell
   .\ShutdownButton.ps1
   ```
4. To convert the script to an executable, use the `Win-PS2EXE` tool:
   ```powershell
   .\ps2exe.ps1 -inputFile .\ShutdownButton.ps1 -outputFile .\ShutdownButton.exe
   ```

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeatureName`).
6. Open a Pull Request.


## Project History

- **Creation Date**: Monday, January 8, 2024
- **Published on GitHub**: Tuesday, March 18, 2025


**Note**: This project was developed using PowerShell and is aimed at users who face issues shutting down their devices quickly. **You must pin the program to the taskbar before running it**, as running it directly will shut down your computer immediately.
