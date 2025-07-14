# XL Inventory UI for FiveM

This is a custom inventory UI designed for FiveM using **HTML**, **CSS**, and **JavaScript (jQuery)**.  
The layout includes a **scrollable inventory grid** and a **vertical hotbar** fixed to the left side of the screen.

## 🌟 Features

- Grid-based inventory system
- Scroll support when item list exceeds height
- Stylish vertical hotbar (6 slots)
- Fully customizable via CSS
- Responsive layout with smooth hover transitions

## 🖼️ UI Overview

- **Inventory (`inv-container`)**  
  - Grid layout with scrollable area
  - Up to any number of items
- **Hotbar (`inv-hotbar`)**
  - Fixed to the **left side** of the screen
  - 8 slots (can be changed)
  - Ideal for quick-use or keybind items

  ![Inventory UI](https://media.discordapp.net/attachments/1370176477198553172/1394270518919565352/DC47D7AF-BF3F-486E-8460-20AED6E38C57.png?ex=6876331c&is=6874e19c&hm=c38fccc56cf8227318e0235d9aa0aa6a059482b353e692a7252afe3cdbe13151&=&format=webp&quality=lossless)


## 📦 Installation (FiveM Resource)

1. Put the `xl_inventory` folder in your `resources/` directory.
2. Add the following to your `server.cfg`: ensure xl_inventory
3. Modify client script to trigger `NUI` open/close if needed.
(You can bind it to a key using `RegisterCommand` or `RegisterKeyMapping`.)

## 🛠️ TODO (Optional Enhancements)

- Add drag & drop support between inventory and hotbar
- Hook into ESX/QBCore inventory data
- Show item icons
- Add item metadata (e.g., quantity, durability)

## 🔗 Credits

- UI: Designed by [YourName]
- jQuery UI: https://jqueryui.com/
- Inspired by: NC Inventory, NoPixel, and other modular UIs

## 📄 License

MIT – free to use, modify, and share.
