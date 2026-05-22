# 🌐 smartphone-browser-app
An easy-to-setup Browser App for GlitchSmith's Smartphone Widget module that allows players to browse a Journal as webpages on their Smartphone.

![Preview Image](https://i.imgur.com/OzcVNhL.png)

This module requires [Smartphone Widget](https://foundryvtt.com/packages/smartphone-widget) module from [The Glitch Smith](https://www.patreon.com/cw/glitchsmith) as this is a custom-built app for the usable Smartphone Widget they created. 

## ☑️ Other Required Plugins
[Socketlib](https://foundryvtt.com/packages/socketlib)

## 📔 Usage
- Enable the app by opening the Smartphone Widget, selecting **Settings** -> **App Store Settings** and then enabling **Browser**.
- Create a Journal named "browserapp" (You can change this name in the module's settings.)
- The first page in this journal will be the browser's homepage. 
- Each page will be its own website, with the name of the page being the address to access it. You should use a common prefix, such as `//` for (e.g `//home` and `//milkshake`).

## 📋 Notes
- Currently supports text and image pages.
- You can use native browser links to link between pages or use this format: `<span class="link" data-target="page">Link text</span>`
- Subpages do not currently matter but I am exploring how to implement them.
- There are two themes currently, Cyberpunk and Neon.
- Search Engine is planned but I need more time.
- This module still isn't exactly where I want it but releasing it to get feedback.

## 💾 Installing
Use the manifest url to add the app:
```
https://raw.githubusercontent.com/teddy-dev/smartphone-browser-app/refs/heads/main/module.json
```

## Support
Support and updates available on my [Discord](https://discord.gg/SUgbgG8).
