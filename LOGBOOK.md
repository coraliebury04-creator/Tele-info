# 📓 Journal de Bord - Téléinfo

Ce document sert de cahier de textes numérique pour le suivi des activités du projet Téléinfo.

---

## 🚀 État Global du Projet
```mermaid
stateDiagram-v2
    [*] --> Initialisation
    Initialisation --> Connexion_Socket : OK
    Connexion_Socket --> Analyse_Trames : En cours
    Analyse_Trames --> Stockage_Data : À faire
