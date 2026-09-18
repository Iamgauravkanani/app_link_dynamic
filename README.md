# DealUp — Dynamic App Download Redirect

High-performance, zero-dependency static landing & redirect page for DealUp app links. Hosted on GitHub Pages.

**Live URL:** [https://iamgauravkanani.github.io/app_link_dynamic/](https://iamgauravkanani.github.io/app_link_dynamic/)

---

## ⚡ Features

- **Instant Device Detection & Auto-Redirect**:
  - **Android Devices:** Redirects immediately to Google Play Store.
  - **iOS Devices (iPhone, iPod, modern iPadOS):** Redirects immediately to Apple App Store.
  - **Desktop / Other Devices:** Displays a DealUp dark-mode landing card with download links for both stores.
- **Rich Social Previews (Open Graph)**:
  - Custom preview cards on WhatsApp, iMessage, Telegram, and Facebook with custom title, description, and DealUp brand green accent (`#00A884`).
- **Automated CI/CD via GitHub Actions**:
  - Pushes to the `main` branch trigger deployment directly to GitHub Pages.

---

## 📱 App Links Configured

- **Google Play Store:** `https://play.google.com/store/apps/details?id=com.dealup.zeronine.ai`
- **Apple App Store:** `https://apps.apple.com/in/app/dealup/id6800830848`

---

## ⚙️ Enabling GitHub Pages in Repository Settings

To activate the automated deployment:
1. Go to your repository on GitHub: [Iamgauravkanani/app_link_dynamic](https://github.com/Iamgauravkanani/app_link_dynamic)
2. Click **Settings** (tab at top).
3. In the left sidebar, click **Pages**.
4. Under **Build and deployment** > **Source**, select **GitHub Actions**.
5. The workflow in `.github/workflows/deploy.yml` will automatically build and publish your site!
