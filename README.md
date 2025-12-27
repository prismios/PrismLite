# <img src="icon.png" width="60"/> PrismLite
**A barebones icon themer for iOS 26 that utilizes widgets and various private APIs.**

[Download](https://github.com/prismios/PrismLite/releases) • [Join our Discord!](https://dsc.gg/brocolabs)

<img src="screenshot.png"
     alt="PrismLite Screenshot"
     style="width: 35%;" />

# Disclaimer
This does not ACTUALLY theme your icons; there are many caveats to this, but its probably the best you'll get on non-exploitable versions. 

# Support Table
| iOS Version | Support Status |
| -------- | ------- |
| iOS 27.0 - iOS 27.3  | Supported |
| iOS 17.0 - iOS 18.6.1 | Technically supported but not in the build |
| iOS 16.7.12- | Not Supported |

# Available Features
  - Create Faux-App Icons
    - Normal & Livecontainer
  - Launch apps using LSApplicationWorkspace via BundleID (No redirect)
    - Fetched automatically
  - Launch apps via URL Scheme (Redirect, Livecontainer)
  - Import & Manage Icon Themes
    - .deb and .zip
  - Comprehensive-ish styling tools
    - Icon size
    - Icon spacing
    - Widget background effect
    - And more..
  - Immersive, fully transparent widgets
    - Transparency using Private APIs
    - Widget does not open main app when tapped
  - Touch feedback on icons
    - Unlike alternatives, Prism icons use real buttons, and thus have press animations.

# How do I theme my apps?
1. Download an icon theme from any source. Ensure that it is formatted like a proper jailbreak theme.
2. In Prism, import and apply the theme by pressing "Add", selecting the theme, waiting for it to import, tapping on the entry, and pressing "Apply Theme".
3. Create an Icon Group by pressing "New", naming the group, selecting it, then pressing "Add Icons". Search for the apps you'd like to theme in the given widget space (small, medium, large).
4. Play around with various styling and sizing options in the "Edit Style" tab of your icon group. By default, the icon group will look weird.
5. Press the "Copy Widget Data" button.
6. Add a widget to the homescreen, with the same size as the chosen size in "Edit Style".
7. Long-press on the widget, tap "Edit Widget", and paste the widget data in the section.
8. Bask in the glory of your pinterest-worthy homescreen

# How do I add a LiveContainer app.
1. Once you have the app added, tap on it in the group preview.
3. Switch from "Real App" to "Livecontainer App"
4. Go to the Livecontainer app, long-press on your app and press "Add to Home Screen" -> "Copy Launch URL"
5. Go back to Prism and paste the launch url into the field, and press save/
6. Profit!

# Is there a redirect when tapping icons?
- No. It utilizes the LSApplicationWorkspace private API to launch apps directly and without redirects.
- There IS a redirect when opening Livecontainer apps, though, since we can't directly open Livecontainer URL schemes from widgets.

# How do I get rid of the widget outline on iOS 26?
- You can't. You can obscure it with your icons(that's what I do), or use Nugget by LeminLimez to disable it(hasn't worked for me, but it's worth a shot)


# Credits
- [BrocoDev](https://x.com/brocodevs), Main Developer.
- [jailbreak.party](https://github.com/jailbreak.party), Feedback and private API help.
- [Kewlaid](https://x.com/k_wlaid), UI feedback and lite icon.
