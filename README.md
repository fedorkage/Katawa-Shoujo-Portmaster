# Katawa Shoujo – Anbernic RG35XX Port

![Screenshot](https://raw.githubusercontent.com/kokseen1/ks-web-client/main/assets/ui/sd-emi-c.png)
![Screenshot](https://raw.githubusercontent.com/kokseen1/ks-web-client/main/assets/ui/sd-hanako-c.png)
![Screenshot](https://raw.githubusercontent.com/kokseen1/ks-web-client/main/assets/ui/sd-lilly-c.png)
![Screenshot](https://raw.githubusercontent.com/kokseen1/ks-web-client/main/assets/ui/sd-rin-c.png)
![Screenshot](https://raw.githubusercontent.com/kokseen1/ks-web-client/main/assets/ui/sd-shizune-c.png)

**Ren'Py 8.3.4 – squashfs build**  
**Tested on Anbernic RG35XX H running MuOS firmware**

---

## ❯ Overview

This is an experimental port of *Katawa Shoujo* to Ren'Py 8.3.4, packaged in squashfs format for use with PortMaster.

The game **launches successfully** and appears to be **fully playable**. No major errors have been observed during testing. Available languages include:  
- English  
- Japanese  
- Spanish  
- French  
- Russian  

**Save/Load** works.  
**Fast-forwarding** works.  
The game **does not crash** during normal gameplay.  
**R18 content** enabled.

---

## ❯ Known Issues

- R18 content **cannot be disabled** at the moment.  
- **Performance is suboptimal**, but acceptable for a visual novel.  
- **Long startup time.**  
- **Controls need refinement** (edit the gptk file).  
- **Video playback is broken**: audio plays, but screen remains black (possibly related to `gl4es` rendering).

---

## ❯ Notes

This port is based on:  
- The Ren'Py 8.0.3 version of Katawa Shoujo by [gcammisa](https://github.com/gcammisa/KatawaShoujo-RenPy8)  (you need to download game files from his repo and put the "game" folder into "katawashoujo" folder.
- To get Russian translation you need to replace some files from "rus" folder to "game"
- The PortMaster version of *Milk inside a bag of milk inside a bag of milk*

I do **not** claim full authorship of this port. I'm not a programmer or developer — just a gamer with some basic computer skills and the help of ChatGPT.

At the moment, this port is **not available in the official PortMaster catalog**, as I believe it still needs polishing and stability improvements. I may consider submitting it in the future once it's more refined.

If you care about this game and have experience with Ren'Py or porting to ARM devices, **any help is welcome**. Please reach out or submit an issue/pull request if you'd like to contribute.

---

## ❯ Feedback and Questions

- [Telegram](t.me/y2kpunk)
- [Email](fedeeeer45@gmail.com)


## ❯ Credits

All assets and content belong to **Four Leaf Studios**, the original developers of *Katawa Shoujo*.  
This port is **unofficial** and **not endorsed** by Four Leaf Studios.  
Please **do not** contact them regarding any problems — open an issue on this GitHub repo instead.

---
