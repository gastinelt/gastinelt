### Théo Gastinel

Jeune développeur autodidacte dans le Vercors. J'aime construire les choses moi-même, de A à Z : mon propre serveur, mes propres outils, sans dépendre du cloud quand je peux l'éviter.


Portfolio : [gastinel.me](https://www.gastinel.me) · Météo en direct : [vercors.me](https://vercors.me)

---

#### Mes projets favoris

| Projet | En bref | Langage |
|---|---|---|
| [Gastinel Weather Studio](https://github.com/gastinelt/gastinel-weather-studio) | Application bureau et mobile pour relever, cartographier et analyser les températures des trous à froid du Vercors. RC-5 en direct par USB, carte hors ligne. | Rust, Tauri |
| [Vercora](https://github.com/gastinelt/vercora) | Jeu d'exploration de montagne solo sur une zone LiDAR reelle de 25 km2 du Vercors.| Moteur maison C++ / Vulkan |
| [Gastinel Write](https://github.com/gastinelt/Gastinel-Write) | Éditeur de texte léger pour matériel modeste : rendu, parseur TTF et DEFLATE faits maison, sans dépendance. | C++20 |
| [IA-86](https://github.com/gastinelt/IA-86) | Étude de l'architecture IA-64 (Itanium, EPIC) et conception d'un nouveau jeu d'instructions. | Architecture (ISA) |
| [Gastinel Covert](https://github.com/gastinelt/Gastinel-Covert) | Gestionnaire de secrets local pour Windows, chiffré (XChaCha20-Poly1305, Argon2id), avec TOTP. | Rust, Slint |

**Minecraft (NeoForge)** : [totoche-tools](https://github.com/gastinelt/totoche-tools) · [gastinel-weather-mod](https://github.com/gastinelt/gastinel-weather-mod) · [sculk-orbs](https://github.com/gastinelt/sculk-orbs) · [timet](https://github.com/gastinelt/timet)

---

#### En ce moment

- **Gastinel Mind** : un assistant IA qui tourne sur mon propre serveur, avec mon modèle **VercorNaf Flash** (basé sur Gemma 4 de Google), spécialisé sur le Vercors. [Voir la documentation.](https://gastinel.me/docu/mind.html)
- **[vercors.me](https://vercors.me)** : les stations météo du massif réunies sur un seul site.

#### Ce que j'utilise

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Vulkan](https://img.shields.io/badge/Vulkan-AC162C?style=flat-square&logo=vulkan&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-0071C5?style=flat-square&logo=intel&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)

![ARM](https://img.shields.io/badge/AArch64-0091BD?style=flat-square&logo=arm&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Slint](https://img.shields.io/badge/Slint-2379F4?style=flat-square&logo=slint&logoColor=white)
![NeoForge](https://img.shields.io/badge/NeoForge-DF6A1D?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Shell Script](https://img.shields.io/badge/Shell_Script-121011?style=flat-square&logo=gnu-bash&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-333333?style=flat-square)

#### Mon infrastructure

Tout ce que je publie tourne sur du matériel que je gère moi-même.

- **Serveur maison** sous Debian. Une carte Tesla P100 (16 Go) fait tourner l'IA en local, sans API extérieure.
- **VPS en frontal** : il reçoit le trafic public et le renvoie vers la maison par un tunnel WireGuard. Rien n'est ouvert directement chez moi.
- **Services en conteneurs Docker**, derrière Caddy (HTTPS automatique) : sites, IA, météo, serveur de jeu, forge Git.
- **Administration** : un [panneau maison](https://github.com/gastinelt/admin-panel) pour surveiller les disques, le GPU, les ventilateurs et les services.
- **Sauvegardes** locales, plus une copie chiffrée hors site.

---

<sub>Fait dans le Vercors.</sub>
