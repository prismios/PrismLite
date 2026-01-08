<p align="center">
  <img src="icon.png" width="90" />
</p>

<h1 align="center">PrismLite</h1>

<p align="center">
  <strong>A barebones icon themer for iOS 26</strong><br/>
  Using Widgets & Private APIs. No Redirects.
</p>

<p align="center">
  <a href="https://github.com/prismios/PrismLite/releases">
    <img src="https://img.shields.io/github/v/release/prismios/PrismLite?style=flat-square">
  </a>
  <a href="https://discord.gg/wTTVQ6jXFb">
    <img src="https://img.shields.io/discord/1410483293249343511?label=Discord&style=flat-square">
  </a>
</p>

---

<p align="center">
  <img src="screenshot.png" width="40%" style="border-radius: 18px;" />
</p>

---

## ⚠️ Warning

Sideload the App With SIDESTORE or EQUIVALENT. Sideloading with a certificate will NOT work.
Updates to this app will not be pushed until an App Store build is launched.

This is a pre-alpha. Expect issues.

---

## ✨ What is PrismLite?

**PrismLite** is a lightweight, widget-based icon theming solution for **non-exploitable versions of iOS**.  
It doesn’t *actually* replace app icons, but it gets about as close as you can without exploits.

By leveraging **widgets**, **private APIs**, and a carefully designed UX, PrismLite attempts to achieve a near-native themed homescreen experience.

---

## ⚠️ Disclaimer

> PrismLite does **NOT** modify system icons.

This approach is **extremely** limited, but on locked-down versions of iOS, this is currently the best achievable result without exploits.

---

## 📱 iOS Support

| iOS Version | Status |
|------------|--------|
| **iOS 26.0 – 26.3** | ✅ Supported |
| iOS 17.0 – 18.6.1 | ⚠️ Technically supported (not in current builds) |
| iOS 16.7.12 and below | ❌ Not Supported |

---

## 🧩 Features

### 🎨 Icon Theming
- Faux app icons
  - Normal apps
  - LiveContainer apps
- Import & manage icon themes
  - `.deb` and `.zip` formats
- Jailbreak-style theme compatibility

### 🚀 App Launching
- Direct app launching via **LSApplicationWorkspace**
  - Launch by Bundle ID
  - No redirect animations
  - Automatically fetched
- URL scheme launching
  - Redirect-based
  - Required for LiveContainer

### 🧱 Widgets & Styling
- Fully transparent widgets
  - Uses private APIs
  - Widget does **not** open main app when tapped
- Advanced styling controls
  - Icon size
  - Icon spacing
  - Widget background effects
  - And more…
- Touch feedback on icons
  - Real buttons
  - Native press animations (unlike alternatives)

---

## 🎨 How to Theme Your Apps

1. Download an icon theme from any source  
   > Make sure it’s formatted like a proper jailbreak theme.
2. Open PrismLite → tap **Add** → select your theme → wait for import  
   Tap the theme entry → **Apply Theme**
3. Create an **Icon Group**
   - Tap **New**
   - Name the group
   - Select it → **Add Icons**
4. Choose the apps you want to theme for the selected widget size  
   *(Small / Medium / Large)*
5. Go to **Edit Style**
   - Adjust sizing and spacing  
   > ⚠️ Default styling usually looks weird. We know.
7. Add a widget to your homescreen
   - Match the widget size exactly
8. Long-press the widget → **Edit Widget**
   - Select your icon group in the "App Group" section
9. Enjoy your Pinterest-worthy homescreen ✨

---

## 📦 Adding a LiveContainer App

1. Add the app normally to your icon group
2. Tap the icon in the preview
3. Switch **Real App → LiveContainer App**
4. Open **LiveContainer**
   - Long-press the app
   - **Add to Home Screen** → **Copy Launch URL**
5. Paste the launch URL into PrismLite and save
6. Profit 💰

---

## 🔁 Redirect Behavior

- **Normal apps:**  
  ❌ No redirect  
  ✔ Uses `LSApplicationWorkspace` for direct launching

- **LiveContainer apps:**  
  ⚠️ Redirect required  
  Widgets cannot directly launch LiveContainer schemes

---

## 🧱 Widget Outline on iOS 26

You unfortunately **cannot fully remove** the widget outline.

### Workarounds:
- Obscure it with icon placement *(recommended)*
- Try **Nugget** by LeminLimez  
  > Results may vary—it hasn’t worked reliably for everyone

---

## 🙌 Credits

- **[BrocoDev](https://x.com/brocodevs)** — Main developer  
- **[jailbreak.party](https://github.com/jailbreak.party)** — Feedback & private API guidance  
- **[Kewlaid](https://x.com/k_wlaid)** — UI feedback & lite icon  

---
