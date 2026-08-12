---
tags:
  - npc
  - npc/one-shot
luogo: Oniria
fazione: Consorzio Galvani
stato: Vivo
---

# 👤 Enea Migliorante, Guardia del Laboratorio
*Ricercatore del Laboratorio di Carla, impiegato anche come guardia. Uomo affabile, ma viscido.*

### 📌 Aspetto e Personalità
- **Tratto Distintivo:** 
- **Voce/Modo di fare:
- **Obiettivo/Segreto:** È innamorato di Carla, ma non della diurna, ma di quella notturna, con la quale ha un rapporto speciale. È stato infettato dalla follia.

### 🔗 Relazioni
- **Alleato di:** [[Carla Sferi, Alta Ricercatrice del Consorzio]]
- **In conflitto con:** [[]]
- **Note personali:** 

### ⚔️ Statistiche e Combattimento

```statblock
name: Enea Migliorante, Guardia del Laboratorio
size: Medio
type: Umanoide
subtype: Umano
alignment: Neutrale Buono
ac: 13
hp: 44
hit_dice: 8d8 + 8
speed: 9 m

# Forza, Destrezza, Costituzione, Intelligenza, Saggezza, Carisma
stats: [11, 14, 12, 10, 13, 14]

# Tiri Salvezza (Rimuovi le righe che non servono)
saves:
  - saggezza: 3

# Abilità (Rimuovi le righe che non servono)
skillsaves:
  - arcano: 2
  - inganno: 4
  - persuasione: 4

# Sensi e Linguaggi
senses: percezione passiva 11
languages: Comune, dialetto Iloniano
cr: 2 # Grado di Sfida (puoi usare anche frazioni come 1/2, 1/4, 1/8)

# AZIONI IN COMBATTIMENTO (Attacchi, Soffi, Magie ad azione singola)
actions:
  - name: Bastone Elettrificato
    desc: "Attacco con arma in mischia: +4 al colpire, portata 1,5 m, un bersaglio. Colpito: 6 (1d8 + 2) danni contundenti più 7 (2d6) danni da fulmine."
  - name: Incantesimi
    desc: "A volontà: [[Light]], [[Thaumaturgy]].<br>2/g: [[Magic Missle]]<br>1/g: [[Hold Person]]"
  - name: 
    
bonus_actions:
  - name: Invisibilità Rapida (Ricarica 5-6)
    desc: "Enea diventa invisibile fino all'inizio del suo prossimo round."
    
reactions:
  - name: Follia Mortale
    desc: Quando Enea scende a 0 HP, può immediatamente effettuare simulatanemaente un'azione di Scatto, di Disingaggio e muoversi di tutto il suo movimento per poi effettuare un attacco.
