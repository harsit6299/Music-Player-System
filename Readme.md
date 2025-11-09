# 🎵 Music Player System

A modular C++ music player built using **Facade**, **Strategy**, and **Adapter** design patterns for clean and extensible architecture.

---

## 🚀 Features
- Unified control via `MusicPlayerFacade`
- Pluggable play strategies (Sequential, Random, Custom)
- Multiple device outputs (Bluetooth, Wired, Headphones)
- Scalable managers for playlist, device, and strategy
- Easy integration and testing

---

## 🏗️ Architecture
- **Facade** – `MusicPlayerFacade` coordinates all modules  
- **Core** – `AudioEngine` handles playback  
- **Strategies** – define playback logic  
- **Devices** – adapters for output hardware  
- **Managers** – handle playlists, devices, and strategies  
- **Factories** – instantiate devices and strategies

---

## 📂 Structure

- core/ → AudioEngine
- managers/ → Playlist, Device, Strategy Managers
- strategies/ → PlayStrategy + Variants
- device/ → Adapters for output devices
- factories/ → DeviceFactory
- models/ → Song, Playlist
- main.cpp → Entry point
