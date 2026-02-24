# 🎮 NEON STRIKE

**Neon Strike** is a fast-paced neon arcade survival shooter built using **HTML5 Canvas**, **Vanilla JavaScript**, and **Tailwind CSS**.
Dodge enemies, shoot strategically, and survive as long as possible against an increasingly aggressive neon swarm.

---

## 🚀 Features

* Smooth 60 FPS gameplay using `requestAnimationFrame`
* Mouse-based aiming & shooting (desktop)
* WASD movement controls
* Touch joystick & fire button for mobile devices
* Progressive difficulty scaling
* Health system with real-time UI updates


---

## 🕹 Controls

### 💻 Desktop

| Action | Key                |
| ------ | ------------------ |
| Move   | `W`, `A`, `S`, `D` |
| Aim    | Mouse              |
| Shoot  | Left Click         |

### 📱 Mobile

| Action | Control            |
| ------ | ------------------ |
| Move   | On-screen joystick |
| Shoot  | Fire button        |

---

## 🛠 Tech Stack

* **HTML5 Canvas** – Rendering & animations
* **Vanilla JavaScript (ES6 Classes)** – Game logic
* **Tailwind CSS (CDN)** – UI styling & layout

---

## 🧠 Game Mechanics

* Enemies spawn off-screen and track the player.
* Enemy speed increases based on your score.
* Shooting enemies increases your score.
* Colliding with enemies drains player health.
* Game ends when health reaches 0.
