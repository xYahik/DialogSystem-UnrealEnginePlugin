# DialogSystem-UnrealEnginePlugin

**DialogSystem-UnrealEnginePlugin** is my private project to simplify the creation and management of dialogues in UnrealEngine.

⚠️ At this time, there are no plans to release the plugin as open source.
## 📷 Screenshots

### 1. Custom Dialog Nodes

This plugin includes additional DialogGraph with several custom Blueprint nodes:

- **Start Dialog**, **End Dialog**, and **Dialog Node** with dynamically generated output pins.
- `Dialog Node` supports parameterized `FText` in the title, description, and answer fields.
- **Action Node** can perform in-dialogue actions with two behavior modes:
  - Wait for action completion
  - Automatically continue to the next step

[![Custom Dialog Nodes](https://i.imgur.com/wGBUN3x.png)](https://i.imgur.com/wGBUN3x.png)
---

### 2. Dialog Controller

Simply dialog controller exposes three key events in Blueprints:

- `StartDialog`
- `NewDialog` — includes dialog title, description, and available options
- `EndDialog`

[![Dialog Controller](https://i.imgur.com/GJzsZdt.png)](https://i.imgur.com/GJzsZdt.png)

---

### 3. Dialog Debug View

Easily debug dialog flow during runtime. The plugin shows the currently active dialog node, helping you trace execution and test logic in real-time.


Example with more complicated dialog graph
[![Dialog Debugging](https://i.imgur.com/wW8CgTr.png)](https://i.imgur.com/wW8CgTr.png)

---

## 🎥 Preview Video v0.1

Video demonstrating the basic capabilities of the plugin

[![DialogSystemVideo](https://img.youtube.com/vi/uyuPNfogjrc/0.jpg)](https://youtu.be/uyuPNfogjrc)
---
