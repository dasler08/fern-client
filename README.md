<h1 align="center">FERN CLIENT</h1>
<p align="center">
  a little companion app for <b>Path of Titans</b>. <b>maps</b>, <b>quest routes</b> and a <b>map overlay</b> you can keep open while you play
</p>

<p align="center">
  <a href="../../releases/latest"><b>⬇ Download the latest version</b></a>
</p>

<img width="1267" height="365" alt="image" src="https://github.com/user-attachments/assets/703d6032-614b-4bcd-af14-f84a6489b3d9" />

##  what it does

| | |
|---|---|
|  **Maps** | **Gondwa**, **Panjura** and **Riparia** with over **21,000 resource spots**, waystones, home caves and place names. drop your own **pins** too |
|  **Quest run** | tell it what your quest needs, click where you are and it plans the **shortest way** to grab everything |
|  **Map overlay** | sits **on top of the game** and lets your clicks go straight through. unlock it to **move, resize and zoom** |
|  **Hotkeys** | show or hide **Fern** and the overlay **without leaving the game** |
|  **Sounds and notices** | a **soft click** and a small **on screen notice** when something turns on or off |
|  **Themes** | **Forest Green**, **Pitch Black**, **Navy Blue**, **Soft Pink** and **Slate Grey** |

<img width="1271" height="528" alt="image" src="https://github.com/user-attachments/assets/d33192f0-a84e-43ae-a469-b3f213250a30" />

<img width="1907" height="868" alt="image" src="https://github.com/user-attachments/assets/ec0e7e91-8ea3-4407-b74f-624d860484ee" />

## ⬇️ download

go to [**Releases**](../../releases/latest) and grab one of these

| file | |
|---|---|
| **Setup** | installs it normally with a **start menu shortcut** and an **uninstaller**. use this one if your not sure |
| **Portable** | **no install**, just put it somewhere and run it |

works on **Windows 10** and **Windows 11** (64 bit)

> [!WARNING]
> windows might show a blue **"Windows protected your PC"** screen the first time because the app isnt signed yet. click **More info** and then **Run anyway**

##  default hotkeys

| action | keys |
|---|---|
| show or hide Fern | <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>F</kbd> |
| map overlay on / off | <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>M</kbd> |
| move and zoom the overlay | <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>K</kbd> |

you can change all of them in **Settings**

> [!IMPORTANT]
> the overlay needs the game in **windowed** or **borderless** mode. fullscreen draws over everything so the overlay wont show

<img width="1270" height="577" alt="image" src="https://github.com/user-attachments/assets/55025e92-fa65-44f2-95c5-5e1b22e4c60a" />

<img width="1267" height="570" alt="image" src="https://github.com/user-attachments/assets/1668bc8f-1c7f-4c23-bd89-58f9b5240b30" />

<img width="1271" height="567" alt="image" src="https://github.com/user-attachments/assets/ac4b0411-c87d-4122-b800-a81adfecc43f" />

## 🛡️ is this a cheat?

> [!NOTE]
> **no.** **Fern** runs on its own next to the game, it **doesnt read, inject into or change Path of Titans** in any way. it just shows maps and info you could find on the web anyway, built to stay inside the **Path of Titans terms of service**

## building it yourself

<details>
<summary>click to see how</summary>
<br />

you need [**Node.js**](https://nodejs.org) and [**Rust**](https://rustup.rs)

```
npm install
npx tauri build
```

the installer ends up in `src-tauri/target/release/bundle/nsis`

</details>

## 💚 credits

* map data and imagery by [**Vulnona**](https://vulnona.com/game/map/)
* **Path of Titans** and its logo and artwork belong to **Alderon Games**

> [!CAUTION]
> **Fern Client** is a **fan project** and isnt affiliated with or endorsed by **Alderon Games**. the code is **MIT licensed**, that doesnt include the map data or any Alderon artwork, those still belong to their owners

##  contact

add me on Discord: **adibado0**

theres **no Fern discord server yet** since its still small. if it grows one will open up
