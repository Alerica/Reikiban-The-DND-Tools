# Reikiban 🧭 

**Reikiban** is a tabletop-style **DnD-inspired sandbox game** where players take on the role of a **Dungeon Master** (DM). It provides tools for map switching, token management, and turn-based gameplay. Built with Unity, Reikiban focuses on **flexibility, creativity, and digital storytelling**.

---

## Core Features & Scripts 🧩 

This section outlines the major features and core scripts that power Reikiban’s gameplay.

<table>
  <tr>
    <th>Feature</th>
    <th>Description</th>
    <th>Main Scripts</th>
  </tr>

  <tr>
    <td><b>Camera Control</b></td>
    <td>Allows players to move and zoom around the board for better visibility and control.</td>
    <td><code>CameraMovement.cs</code></td>
  </tr>

  <tr>
    <td><b>Dungeon Master Tools</b></td>
    <td>Main control system that lets the DM manage gameplay elements such as maps, turns, tokens, and visibility.</td>
    <td><code>DMManager.cs</code></td>
  </tr>

  <tr>
    <td><b>Grid System</b></td>
    <td>Renders a customizable grid over the map to assist with positioning and movement.</td>
    <td><code>GridRenderer.cs</code></td>
  </tr>

  <tr>
    <td><b>Layer System</b></td>
    <td>Each map supports up to 5 layers (e.g., background, objects, fog of war). Players can toggle between them.</td>
    <td><code>LayerManager.cs</code>, <code>MapTabController.cs</code></td>
  </tr>

  <tr>
    <td><b>User Interface</b></td>
    <td>Handles menus, settings, and interactive elements like buttons and panel switching.</td>
    <td><code>UIManager.cs</code>, <code>NetworkUI.cs</code></td>
  </tr>

  <tr>
    <td><b>Map Management</b></td>
    <td>Supports switching between maps and uploading external map files for gameplay sessions.</td>
    <td><code>Map.cs</code>, <code>MapSwitcher.cs</code></td>
  </tr>

  <tr>
    <td><b>Token System</b></td>
    <td>Manages all units and entities placed on the board. Tokens can be spawned, dragged, and removed dynamically.</td>
    <td><code>Token.cs</code>, <code>TokenData.cs</code>, <code>TokenManager.cs</code>, <code>TokenSpawner.cs</code>, <code>TokenSpawnerUI.cs</code>, <code>TokenButton.cs</code></td>
  </tr>

</table>

---

## Networking (Experimental)  🌍 

- Reikiban includes early-stage support for **multiplayer Dungeon Master sessions** using **Unity NetCode**.
- The `NetworkUI.cs` handles player connections and basic data sync.
- Multiplayer development is still a work-in-progress and may not be stable.

---

## Features Summary ⚙️ 

- Zoomable, pannable camera  
- Dungeon Master controls  
- Multi-layered map editing  
- Map import & switching  
- Token creation and control  
- Experimental multiplayer support

---

## Controls  🎮 

| Input        | Action                      |
|--------------|------------------------------|
| Left Click   | Select or place tokens       |
| Drag         | Move tokens on grid          |
| Scroll       | Zoom camera in/out           |
| Right Click  | Pan camera                   |
| Tab / Hotkeys | Switch map tabs/layers     |

---
## Gameplay
<img src="https://github.com/Alerica/Reikiban-The-DND-Tools/blob/main/Reikiban-Clip.gif" alt="1" style="width:100%;height:auto;">

---
## Project Goals 🧠 

**Reikiban** is a sandbox for storytelling and encounter-building. It’s inspired by digital tools like *Roll20*, but focused on **local control**, **offline tools**, and **custom extensions**. Future features may include dice rolling, card draws, and game-state saving.

---

## Status 🚧 

This project is in **active development**. Systems may change or expand as features are added.

---
