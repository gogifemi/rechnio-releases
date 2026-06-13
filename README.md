# Rechnio Downloads & Updates 🚀

Welcome to the download and release repository for **Rechnio** — the offline-first freelancer toolkit for Germany (Invoice, Expenses, EÜR & Steuer, and Offer Builder).

Here, you can always find the latest official versions of Rechnio for Windows and macOS, as well as instructions for mobile and tablet devices.

---

## 📦 Download & Install Rechnio

To get started, go to our **[Releases Page](https://github.com/gogifemi/rechnio-releases/releases)** and download the correct installer for your computer, or follow the mobile instructions below:

### 🪟 Windows
1. Download **`Rechnio-Setup.exe`** from the latest release.
2. Run the file on your computer to install.
3. **Auto-Updates:** Once installed, Rechnio will automatically check for updates, download them in the background, and let you know when they are ready to install.

### 🍏 macOS (Mac)
1. Download **`Rechnio.dmg`** from the latest release.
2. Double-click the downloaded file and drag the Rechnio icon into your **Applications** folder.
3. **Manual Updates:** To update Rechnio on your Mac, simply visit this page, download the latest `Rechnio.dmg`, and drag it into your Applications folder (replacing the old version).

### 📱 Mobile & Tablet (iOS & Android)
Rechnio can be installed as a **Progressive Web App (PWA)** on any smartphone or tablet, allowing you to manage your freelance tasks on the go.
1. Open the web browser on your phone or tablet and visit **[rechnio.gikstudio.com](https://rechnio.gikstudio.com)**.
2. Follow these quick steps to install:
   - **iPhone & iPad (Safari):** Tap the **Share** button (the square with an up arrow) at the bottom, scroll down, and tap **Add to Home Screen**.
   - **Android Devices (Chrome):** Tap the **Menu** button (three dots) in the top-right corner and tap **Install App** (or **Add to Home Screen**).
3. **Automatic Updates:** Since the mobile version runs as a PWA, it updates automatically in the background whenever you open it. No manual file downloads are required!

---

## 🔒 Privacy & Security

Rechnio is designed to be **fully offline and local**. 
- Your client data, invoices, and financial records never leave your computer.
- We do not store or track your sensitive business information on any servers.
- This repository is only used to deliver the application files and update packages safely to your device.

---

<details>
<summary>🛠️ For Developers / Technical Details</summary>

This repository acts as the update server for `electron-updater`.

- **Windows Auto-Updates:** Powered by the `latest.yml` file which contains the version metadata and file hashes.
- **Mac Releases:** Distributes standard `.dmg` files.
- **Automated Builds:** Builds are compiled and deployed automatically via GitHub Actions in the main development repository when a version tag (e.g. `v1.3.6`) is pushed.

</details>

---

*Need help? Contact us at [rechnio@gikstudio.com](mailto:rechnio@gikstudio.com) or visit [rechnio.gikstudio.com](https://rechnio.gikstudio.com).*