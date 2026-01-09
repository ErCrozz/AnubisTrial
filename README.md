# Anubi's Trial

Un gioco **survivor in terza persona** sviluppato con Unreal Engine 5.3, ambientato in un'arena ispirata all'antico Egitto.

## Descrizione

Il giocatore viene messo alla prova in un ambiente ostile fatto di templi, rovine e strutture monumentali, dove la sopravvivenza dipende dalla capacità di resistere a continue ondate di nemici e di sfruttare lo spazio circostante.

### Movimenti e Animazioni

Il personaggio dispone di un sistema di movimento fluido e reattivo:
- **Capriola evasiva** – permette di schivare rapidamente gli attacchi nemici
- **Melee attack** – combo di attacchi ravvicinati per eliminare i nemici

### Caratteristiche Tecniche

Il progetto è stato realizzato utilizzando **Blueprint coding** per la gestione della logica di gioco, del movimento del personaggio e del comportamento dei nemici. Grande attenzione è stata dedicata alla costruzione dell'atmosfera visiva attraverso:
- Illuminazione dinamica
- Ombre in tempo reale
- Materiali fisicamente plausibili

### Gameplay

L'esperienza di gioco è pensata come una vera e propria prova di resistenza: il posizionamento del giocatore, il controllo della camera e la leggibilità della scena diventano elementi chiave per sopravvivere più a lungo possibile.

*Anubi's Trial* punta a trasmettere tensione e senso di sfida costante, valorizzando l'azione e l'impatto visivo più che la complessità delle meccaniche.

---

## Requirements

- Unreal Engine 5.3
- Git LFS (for binary assets)

## Plugins

- AnimationLocomotionLibrary
- AnimationWarping
- MotionWarping
- Volumetrics
- ApexDestruction

## Getting Started

1. Clone the repository with LFS:
   ```bash
   git lfs clone https://github.com/ErCrozz/AnubisTrial.git
   ```

2. Open `Crozz_Project.uproject` in Unreal Engine 5.3

## Project Structure

```
├── Config/         # Project configuration files
├── Content/        # Game assets (Characters, Weapons, Levels, etc.)
└── Crozz_Project.uproject
```

## License

All rights reserved.
