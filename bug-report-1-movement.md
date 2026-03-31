# 🐞 Bug Report: Character Movement Instability on Slopes & Staircases

> **Bug ID:** QA-001  
> **Platform:** PC  
> **Category:** Gameplay / Physics  
> **Severity:** Medium  
> **Priority:** High  

---

## 🧾 Description
When the player character moves across inclined surfaces such as slopes or staircases, movement becomes unstable. The character may slide unexpectedly, jitter, or fail to maintain proper footing, affecting control consistency and immersion.

---

## 🔁 Steps to Reproduce
1. Launch the game and load into an open-world environment  
2. Locate a sloped surface or staircase  
3. Move the player character upward and downward repeatedly  
4. Change movement speed (walk/run/sprint)  
5. Observe character behavior during traversal  

---

## ✅ Expected Result
- Smooth traversal across slopes and stairs  
- Movement speed and animations adapt correctly to incline  
- No sliding, jittering, or clipping  

---

## ❌ Actual Result
- Character slides backward on slopes  
- Jittering during staircase traversal  
- Foot placement misaligned with surface  
- Movement speed becomes inconsistent  

---

## 📊 Repro Rate
Occurs frequently (~70–80%), especially on steep slopes and narrow staircases  

---

## 🎯 Impact
- Breaks immersion  
- Affects movement control and navigation  
- Can interfere with combat or mission flow  

---

## 🔍 Possible Cause (Analysis)
- Incorrect collision detection on inclined surfaces  
- Improper slope angle handling in movement physics  
- Mismatch between animation system and physics controller  