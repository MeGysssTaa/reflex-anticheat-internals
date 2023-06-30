# Reflex Anticheat — Internals

![][reflex-logo-big]




## ℹ️ About

**Reflex** was a premium server-side anticheat for Minecraft (Bukkit), which was actively developed from 2016 to 2021. This repository serves as its primary legacy. It hosts the latest available anticheat version, which is downloadable and runnable for free; detailed low-level descriptions of Reflex's checks and techiques that it used to fight cheating and provide user friendliness; "stories" and reasoning on why the project was discontinued; and maybe more.

Everything in this repository is licensed under the [CC BY 4.0 License][license] (see the bottom of this file/page for details).

Many of the documents in this repository might seem large for most people, but a **TL;DR** version is provided in the beginning of most of them, which don't carry the emotion or some important nuances, but still outline the most important information (summary).




## 📚 Table of Contents

1. Maintenance / Story

   1.1. [Why Reflex was discontinued][why-discontinued]

   1.2. [The current state of Reflex and the dev team][current-state]

2. [Download the latest version of Reflex with all Reflex Moonlight features unlocked for free][download-reflex]

3. Technical details

   3.1. [Prerequisites][prerequisites]

   3.2. KillAura checks (+ AimBot, AimAssist, TriggerBot, and some more)
   
   - 3.2.1. [Description of the `ka.acr` check — Perfectly smooth rotations][check.ka.acr]

   - 3.2.2. [Description of the `ka.blc` check — "Lazy Aim" and aiming inconsistencies][check.ka.blc]
  
   - 3.2.3. [Description of the `ka.ra` check — "To click, or not to click" accuracy][check.ka.ra]
  
   - 3.2.4. [Description of the `ka.yst` check — Absurdly complicated statistical inference for Aimbot detection][check.ka.yst]
  
   3.3. Lag detection

   - 3.3.1. [Description of the `badpcks.spf` check — Abusing MC inventory to detect Ping Spoof / Fake Lag][check.badpcks.spf]
   





## 💡 Notes

Contents disclosed in this repository are, of course, not exhaustive. There are quite many other checks and tricks in Reflex which will stay behind the curtains, at least for now. We may be expanding the list of published materials with new exciting stuff later (or maybe not). Anyway, we hope that the entire Minecraft community will benefit from this all in some way!







---

## 📄 License

### ⚠ IMPORTANT: This repository also hosts some pics, just for the memes, which are used throughout the files. They belong to their respective owners (if any), no claims made for them by Reflex Development Team. If you have any problems with them, please let us know, and we'll address any issues immediately!

[Reflex Anticheat Internals][reflex-anticheat-internals] © 2023 by Reflex Development Team: [DarksideCode (German)][dev-german], [sinnlosername (Florian)][dev-florian], [StevenKGER (Steven)][dev-steven], Manic97 (Michael) is licensed under [CC BY 4.0][license]. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/

[license]: http://creativecommons.org/licenses/by/4.0

[reflex-anticheat-internals]: https://github.com/MeGysssTaa/reflex-anticheat-internals

[dev-german]: https://github.com/MeGysssTaa

[dev-florian]: https://github.com/sinnlosername

[dev-steven]: https://github.com/StevenKGER

---

## [🏠 Return to main page][reflex-anticheat-internals]

---









[reflex-logo-big]: https://github.com/MeGysssTaa/reflex-anticheat-internals/blob/8a35007fca0904771d767a1ad466e1d140a79ba6/assets/Reflex%20Logo%20Big.png

[download-reflex]: https://github.com/MeGysssTaa/reflex-anticheat-internals/releases/tag/v11.3-5-27732ae-MOONLIGHT

[why-discontinued]: https://github.com/MeGysssTaa/reflex-anticheat-internals/blob/main/texts/1.1.%20Why%20Reflex%20was%20discontinued.md

[current-state]: https://github.com/MeGysssTaa/reflex-anticheat-internals/blob/main/texts/1.2.%20The%20current%20state%20of%20Reflex%20and%20the%20dev%20team.md

[prerequisites]: https://github.com/MeGysssTaa/reflex-anticheat-internals/blob/main/texts/3.1.%20Prerequisites.md

[check.ka.acr]: https://github.com/MeGysssTaa/reflex-anticheat-internals/blob/main/texts/3.2.1.%20Description%20of%20the%20%60ka.acr%60%20check.md

[check.ka.blc]: https://github.com/MeGysssTaa/reflex-anticheat-internals/blob/main/texts/3.2.2.%20Description%20of%20the%20%60ka.blc%60%20check.md

[check.ka.ra]: https://github.com/MeGysssTaa/reflex-anticheat-internals/blob/44278f9677985ca0228623f2664a3f97afa76dc7/texts/3.2.3.%20Description%20of%20the%20%60ka.ra%60%20check.md

[check.ka.yst]: https://github.com/MeGysssTaa/reflex-anticheat-internals/blob/bded082d37bfc4f3b49629e79b0ee0fc6849bf6e/texts/3.2.4.%20Description%20of%20the%20%60ka.yst%60%20check.md

[check.badpcks.spf]: https://github.com/MeGysssTaa/reflex-anticheat-internals/blob/5a79038e28d6984371c741b0d2981b8eba795444/texts/3.3.1.%20Description%20of%20the%20%60badpcks.spf%60%20check.md







