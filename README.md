# 🌌 Arise Client

**The ultimate go-to multitool for modifying and managing the _SchoolBoy Runaway_ game with ease.**  
Created with 💙 by **Fusion Softworks**

---

## 📸 Main Menu

![Image of Main Menu](https://cdn.discordapp.com/attachments/1360175889647796268/1367469766264225802/e.png?ex=6814b2f6&is=68136176&hm=add4d319a7f67b64d33d151c95cbc82b59dca53fcbf52411993e948ac75f63b8&)

---

## 🎮 Features & Modules

### 1. 🔍 **Monitor Pass**
- **Function**: Monitors and logs current password for _SchoolBoy Runaway_.
- **Use Case**: For retrieving the in-game password in real-time from files.
  
![Monitor Pass Function](https://cdn.discordapp.com/attachments/1360175889647796268/1367469765857247323/b.png?ex=6814b2f6&is=68136176&hm=3c439bc4b3a21e94e0f7b5a1faf10e3307acbd7abcd4731355dc629f1c1573ce&)

---

### 2. 🔐 **Custom Pass**
- **Menu Options**:
  - `[1] Set New Password` — Manually sets a new in-game password (must be 4-digit).
  - `[2] Reset Password (Default)` — Restores original game DLL from GitHub.
  - `[3] Back to Main Menu`
- **How It Works**: Replaces the `Assembly-CSharp.dll` with a modified one and sets a custom password provided by the user.

![Custom Pass Function](https://cdn.discordapp.com/attachments/1360175889647796268/1367469765571903639/c.png?ex=6814b2f6&is=68136176&hm=ad5a93ef33f9b3cfdec74a48492236786be6871851f922174653a4c31f9df2bf&)

---

### 3. 📦 **Presets Manager**
- **Menu Options**:
  - `[1] Download Presets` — Choose from 3 game-modifying presets:
    - Preset 1: Roof-related tweaks
    - Preset 2: Lose scene + kitchen gate + spray tweaks
    - Preset 3: Spray in dad’s room
  - `[2] Reset Presets (Default)` — Reverts game back to original DLL
  - `[3] Back to Main Menu`
- **How It Works**: Downloads specific versions of the DLL and applies them.

![Presets Manager](https://cdn.discordapp.com/attachments/1360175889647796268/1367469765240684604/k.png?ex=6814b2f6&is=68136176&hm=760d45398c5af80ce273be246245f0b9f4357ca406e984bc856658b925c96413&)

![Presets Available](https://cdn.discordapp.com/attachments/1360175889647796268/1367469767094698086/n.png?ex=6814b2f6&is=68136176&hm=74a0d74121e7e977747ea40bab06727e14ae24a643f6b94ef5be92094446e184&)

---

### 4. 🛠️ **Mod Menu (In-Game)**
- **Registry-based** menu switcher for enabling/disabling in-game mod mode.
- **Menu Options**:
  - `[1] Turn Mod Menu ON`
  - `[2] Turn Mod Menu OFF`
  - `[3] Check Current Status`
  - `[4] Back`
  
  ![Mod Menu](https://cdn.discordapp.com/attachments/1360175889647796268/1367469766847238296/m.png?ex=6814b2f6&is=68136176&hm=75e2cf1f860c2fdacc74591e16306be05e7d216bfd599508627117465aad2557&)

- **Registry Path**:  
  `HKCU\SOFTWARE\Linked Squad\SchoolBoy Runaway`  
  → `isOnMenuMode_h1994367598`

---

### 5. ⚙️ **Settings**
- **Menu Options**:
  - `[1] Toggle Webhook Logging` — Enable/disable logging events to a Discord webhook.
  - `[2] Set Webhook URL` — Manually set the Discord webhook URL.
  - `[3] Test Webhook` — Sends a test embed to verify setup.
  - `[4] Back`

![Settings Menu](https://cdn.discordapp.com/attachments/1360175889647796268/1367469766519816377/7.png?ex=6814b2f6&is=68136176&hm=8823633a1faab04a39af2867007ec2aa357289b4730dd5f07c74eb2327db7d24&)

- **Webhook Usage**:
  - Logs when the app starts, exits, or toggles logging.
  - Supports embed messages with icons and timestamps.

- **Persistent Storage**: Saves webhook URL and status in Windows Registry at  
  `HKCU\Software\FusionClient`

---

### 6. ❌ **Exit**
- Safely terminates the client after saving all settings and logging the exit event (if enabled).

---

## 📆 Download

🔎 Get the latest stable build from the [Releases Page](https://github.com/LunarArise/AriseClient/releases/latest/download/ariseclient.exe)

Extract the `.zip`, run the single `.exe`, and enjoy!  
No dependencies or installers required thanks to embedded DLLs (Costura.Fody).

---

## 👥 Credits

**Owners:**
- `Mark` → _markedas_ / Discord: `1318285859023229020`
