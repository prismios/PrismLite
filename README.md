# PrismLite
**A barebones icon themer for iOS 26 that utilizes widgets and various private APIs.**

[Download](https://github.com/prismios/PrismLite/releases) • [Join our Discord!](https://dsc.gg/brocolabs)

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
5. Add a widget to the homescreen, with the same size as the chosen size in "Edit Style".
6. Long-press on the widget, tap "Edit Widget", and select your newly created group in the "App Group" section.
7. Profit 🔥

# How do I get rid of the widget outline on iOS 26?
- You can't. You can obscure it with your icons(that's what I do), or use Nugget by LeminLimez to disable it(hasn't worked for me, but it's worth a shot)


# Credits
- [BrocoDev](https://x.com/brocodevs), Main Developer.
- [jailbreak.party](https://github.com/jailbreak.party), Feedback and private API help.
- [Kewlaid](https://x.com/k_wlaid), UI feedback and lite icon.
