# 🚀 Space SHMUP (CS382 Game Design & Development)
- **Play Online:** https://zunehrabanu.github.io/SpaceShmup/

## 🎯 Overview
Space SHMUP is a hybrid space-shooter game completed for **Bond Chapters 31–32**. The player controls a ship, shoots enemies falling from above, collects power-ups, and survives while earning points. This project includes custom models, audio, particle effects, and a WebGL deployment hosted via GitHub Pages.

---

## 🧩 Project Requirements (from course)

### **✔ Base Requirement**
- Completed the **Space SHMUP tutorial from Bond Chapter 31**

### **✔ Graded Criteria**
| Requirement | Points | Status |
|------------|--------|--------|
| Increase to **5 enemies** (Chapter 32) | 5 pts | ✔ Completed |
| Enemies damage the player | 2 pts | ✔ Implemented |
| Shooting works correctly | 1 pt | ✔ Working |
| Scrolling **starfield background** (Chapter 32) | 1 pt | ✔ Included |
| Make the game cooler in a meaningful way | 1 pt | ✔ Added VFX + sound |
---

## 🧩 Features & Implementation

### **✔ Tutorial Foundation**
- Implemented from Bond **Chapter 31 & Chapter 32**
- Includes movement, shooting, enemy spawning, collisions, and power-ups

### **✔ Correct Unity Version**
- **Unity 2021.3.33f1 (LTS)** — matches textbook compatibility

### **✔ 5 Enemy Types**
- Multiple prefabs spawn randomly above the screen
- Custom models replace default tutorial enemies
- Each has unique movement + proper capsule colliders

### **✔ Power-Ups System**
- Randomized drop based on enemy probability
- Player can upgrade weapons upon collection

## 💥 Enhancement (Make the Game Cooler)

### **1️⃣ Spark Particle Explosion on Enemy Death**
- Custom particle effect triggers when enemies explode
- Includes red burst to show impact visuals
- Auto-destroy after short duration

### **2️⃣ Sound Effects**
- Music tracks added to the scene for continual gameplay audio
- Loops automatically while playing

## 🎮 How to Play
1) Move with WASD / Arrow Keys
2) Shoot using Space / Left Click
3) Destroy enemies to earn score
4) Avoid enemy collisions
5) Collect power-ups to upgrade weapons and survive longer
