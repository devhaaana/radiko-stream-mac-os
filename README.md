# Radiko-Stream-Mac-OS

Radiko-Stream can record the [radiko.jp](https://radiko.jp/) programs outside of Japan.

## Warning

**Please do not use this project for commercial use. Only for your personal, non-commercial use.**

All necessary resources and files are already embedded within the application.

You don’t need to download or configure any additional components.

## Technologies

- `Python` : 3.12
- `PyQt`

# Technical Details

The authentication of PC(html5) version radkio validates user's location via IP address.

However, the android version of radkio validates user provided by GPS information, not via user's IP address.

# Getting Started

## Installation

- You can install it **locally:**
  ```console
  $ git clone https://github.com/devhaaana/Radiko-Stream-Mac-OS.git
  $ cd Radiko-Stream-Mac-OS
  ```

## Usage

**1. Run the Application**

- Simply double-click the **main** executable file to start the application.

**2. For macOS Users**

- If you encounter a security warning when trying to run the application:

1. Open **System Settings** > **Privacy & Security** >  **General**.
2. Look for a message about the blocked app and click  **Allow Anyway**.
3. Attempt to open the app again, and if prompted, choose  **Open**.

## Reference

[rajiko](https://github.com/jackyzy823/rajiko)

[Radiko-Stream](https://github.com/devhaaana/Radiko-Stream.git)
