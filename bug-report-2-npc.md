# 🐞 Bug Report: Player Falls Through World Near NPC Vendor

> **Bug ID:** QA-002  
> **Platform:** PC  
> **Category:** Gameplay / Physics / Interaction  
> **Severity:** Critical  
> **Priority:** Urgent  

---

## 🧾 Description
When the player approaches an interactable NPC vendor, the character occasionally clips through the ground and falls out of the map (world), making the game unplayable and requiring a restart or reload.

---

## 🔁 Steps to Reproduce
1. Launch the game and enter an area with NPC vendors  
2. Approach a vendor at normal or sprint speed  
3. Initiate interaction or stop within interaction range  
4. Observe player position and collision behavior  

---

## ✅ Expected Result
- Player remains grounded  
- Interaction prompt triggers correctly  
- Stable collision with environment  

---

## ❌ Actual Result
- Player clips through ground near NPC  
- Falls endlessly below the map  
- Interaction fails to trigger  
- Game state becomes unrecoverable without reload  

---

## 📊 Repro Rate
Occurs intermittently (~20–30%), more frequently when approaching at higher speed  

---

## 🎯 Impact
- Critical gameplay break  
- Player progression blocked  
- Requires restart or checkpoint reload  
- Major negative user experience  

---

## 🔍 Possible Cause (Analysis)
- Missing or misaligned collision mesh near NPC  
- Interaction trigger overlapping with terrain collision  
- Physics breakdown during interaction state transition  