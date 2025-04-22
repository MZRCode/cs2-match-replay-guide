# 🎮 CS2 Match Replay Guide: Download & Watch Your Game Demos Easily
> Step-by-step guide for downloading and watching your CS2 match replays with demo commands and controls.

---

## ✅ How to Watch CS2 Match Replays
1. Visit your Steam match history page (example for Wingman mode):
   ```
   https://steamcommunity.com/id/YOUR_STEAM_ID/gcpd/730?tab=matchhistorywingman
   ```
2. Download the `.dem.bz2` replay file of a match.
3. Extract the file using [7-Zip](https://www.7-zip.org/) or [WinRAR](https://www.win-rar.com/).
4. Move the extracted `.dem` file into:
   ```
   C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo
   ```
5. Launch **Counter Strike 2**, then open the developer console *(by pressing `~` or `` ` ``)* and type the following:
   ```
   playdemo FILENAME
   ```

---

## 🎥 Demo Controls
- Type `demoui` in the console to open the demo UI panel.
- Type it again for more advanced controls.
- Type it a third time to hide the panel.

---

## 🔗 Supported Match Types
Your match history can be accessed using this base URL:  
```
https://steamcommunity.com/id/YOUR_STEAM_ID/gcpd/730?tab=MATCH_TYPE
```

Replace:
- `YOUR_STEAM_ID` with your actual Steam username or numerical ID
- `MATCH_TYPE` with one of the following:

| Match Type     | Tab Suffix                |
|----------------|---------------------------|
| Premier        | `matchhistorypremier`     |
| Competitive    | `matchhistorycompetitive` |
| Wingman        | `matchhistorywingman`     |
| Operation Hydra| `matchhistoryophydra`     |

---

## ℹ️ Tips
- Replace `YOUR_STEAM_ID` with your actual Steam profile ID or custom username.
- If the demo doesn't load, the file may be corrupted or incompatible.

---

## 🤝 Contributing & Thanks
If you found this guide helpful:
- ⭐ Star the repo to support it
- 📢 Share it with your friends
- 🌍 Contribute by translating the guide into other languages

Want to help improve the guide? Check out the [CONTRIBUTING.md](CONTRIBUTING.md) for how to contribute.

Thanks to everyone who helps make CS2 more accessible for everyone!

---

## 📄 License
MIT License free to use, free to modify.
```