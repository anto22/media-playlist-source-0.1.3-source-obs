# 📋 Media Playlist Source

![OBS](https://img.shields.io/badge/OBS-Plugin-black.svg)
[![License: GPL2](https://img.shields.io/badge/License-GPL2-green.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
[![Platform](https://img.shields.io/badge/Platform-Arch_Linux-blue.svg)](#)
[![Status](https://img.shields.io/badge/Status-Stable-brightgreen.svg)](#)
[![OBS](https://img.shields.io/badge/OBS-Plugin-black.svg)](https://obsproject.com)

**Un plugin permettant de lire des playlists de médias (vidéo/musique) directement dans OBS Studio.**

---

## 🧠 Overview

**Media Playlist Source** est un plugin qui remplace avantageusement le VLC Video Source.  
Il permet de créer et gérer des playlists de fichiers multimédias (vidéos, musiques, etc.) avec lecture automatique, shuffle, boucle, etc.

Idéal pour les streamers qui veulent lancer plusieurs clips ou musiques sans avoir à tout reconfigurer à chaque fois.

---

## ✨ Features

- ✅ Lecture de playlists vidéo et audio
- ✅ Gestion simple (ajout, suppression, ordre)
- ✅ Options de lecture (shuffle, repeat, etc.)
- ✅ Léger et bien intégré à OBS
- ✅ Mise à jour régulière

---

## 🚀 Installation

```bash
# 1. Installer les outils de base
sudo pacman -S --needed base-devel git

# 2. Cloner le repo
git clone https://github.com/anto22/obs-media-playlist-source.git
cd obs-media-playlist-source

# 3. Compiler et installer
makepkg -si
