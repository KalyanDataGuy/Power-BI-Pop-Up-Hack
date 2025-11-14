# 📊 Power BI Pop-Up Hack — KalyanDataGuy Cheatsheet Geek Edition
Part 1 of Data Analytics Cheatsheets
**by KalyanDataGuy**

---

Annoyed by Power BI’s **“Enter your email” pop-up**?  
Silence it once and for all.  
This simple **registry tweak** keeps your workflow clean, letting you focus on dashboards, insights, and real analytics — not clicks.  

---

## 🔍 Why This Hack Exists

Learners, developers, and analysts often waste time dismissing the same pop-up every launch.  
This hack is for **any local Power BI installation**, offline devs, and learners wanting a distraction-free workspace.  

---

## ⚡ The Hack — Step by Step

1. **Close Power BI** → Press `Win + R` → type `regedit`  
2. Navigate to:  
HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft
3. **Create New Key:** `Microsoft Power BI Desktop`  
4. **Add DWORD (32-bit):** `ShowLeadGenDialog = 0`  
5. **Relaunch Power BI** ⚡

✅ **Geek Tip:** Always **backup your registry** before editing. This tweak only affects local builds; cloud workspaces are untouched.  

---

## 📊 Hack Table — Quick Reference

| Problem                   | Default Behavior                  | Hack Outcome                         |
|----------------------------|---------------------------------|-------------------------------------|
| Lead generation pop-up      | Appears every launch             | Silenced via registry tweak          |
| Workflow interruption       | Breaks focus                     | Smooth, distraction-free workflow    |
| Local dev safety            | Risk if editing registry blindly | Backup first → safe execution        |

---

## 📂 Files in this Repo

| File                           | Description                                    |
|--------------------------------|-----------------------------------------------|
| `PowerBI_PopupFix.png`          | 2-page cinematic visual of the hack          |
| `README.md`                     | Story, concept, steps, geek tips, and table |

---

<img width="1536" height="1024" alt="KalyanDataGuy PowerBI" src="https://github.com/user-attachments/assets/9433dec3-a52e-4d4e-b4e8-141ab7db4684" />

---

## ⚡ Tags

#powerbi #dataanalytics #workflow #analytics #dashboards  
#learning #productivity #kalyandataguy #cheatsheet #geekedition  

---

## 👤 About the Author

**KalyanDataGuy** — blending data storytelling and analytics with workflow optimization for real-world use.  

---

*✨ Stop pop-ups 🚫, keep building 📊, and let your dashboards guide you 🌀.*

---
