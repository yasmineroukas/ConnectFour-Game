# 🎮 Puissance 4 - Jeu Classique

[![Play Online](https://img.shields.io/badge/Jouer_en_ligne-Live_Demo-brightgreen)](https://connect-four-game-wczt.onrender.com/)

![Aperçu du jeu](https://via.placeholder.com/800x400?text=Capture+du+jeu+Puissance+4)

## 🌟 Aperçu
Implémentation web complète du célèbre jeu de stratégie avec :
- Interface intuitive avec animations fluides
- Détection intelligente des combinaisons gagnantes
- Expérience responsive (mobile/desktop)

## ⚙️ Architecture
```mermaid
flowchart LR
    F[Frontend] -->|HTTP| B[Backend]
    B -->|JSON| F
    style F fill:#f9f,stroke:#333
    style B fill:#0af,stroke:#333
