---
tags:
  - npc
luogo: Oniria
fazione: Consorzio Galvani
stato: Vivo
---

# 👤 Carla Sferi, Alta Ricercatrice del Consorzio
Alta ricercatrice del [[Consorzio Galvani]]; stacanovista dal sonno disturbato.

### 📌 Aspetto e Personalità
- **Tratto Distintivo:** Spessi occhiali tondi e profonde occhiaie.
- **Voce/Modo di fare:** 
- **Obiettivo/Segreto:** Vuole sviluppare il golem più evoluto della storia; cerca di sopprimere la sua libido a favore del lavoro.

### 🔗 Relazioni
- **Alleato di:** [[Vittorio Galvani, Console]]
- **In conflitto con:** [[]]
- **Note personali:** 

### ⚔️ Statistiche e Combattimento

Carla non è una combattente e non ha nessun tipo di competenza nel combattimento. Agisce quindi come una Commoner:
```statblock
monster: Commoner
```

Se addormentata, il suo subconscio magico si manifesta trasformandola in:

```statblock
name: Carla Sferi, Dormiente
size: Medio
type: Umanoide
subtype: Umano
alignment: Neutrale Buono
ac: 15
hp: 42
hit_dice: 8d8 + 2
speed: 9 m

# Forza, Destrezza, Costituzione, Intelligenza, Saggezza, Carisma
stats: [8, 14, 12, 16, 13, 10]

# Tiri Salvezza (Rimuovi le righe che non servono)
saves:
  - intelligenza: 5
  - saggezza: 3

# Abilità (Rimuovi le righe che non servono)
skillsaves:
  - arcano: 5
  - percezione: 3

# Resistenze, Immunità e Vulnerabilità (Rimuovi o lascia vuoto se non presenti)
condition_immunities: affascinata, addormentata

# Sensi e Linguaggi
senses: percezione passiva 13
languages: Comune, dialetto Iloniano
cr: 2 # Grado di Sfida (puoi usare anche frazioni come 1/2, 1/4, 1/8)

# TRATTI E ABILITÀ PASSIVE (es. Tattiche del Branco, Incantesimi Silenti, ecc.)
traits:
  - name: Resistenza della Dormiente
    desc: "Se Carla fallisce un TS, può scegliere invece di passarlo. Se lo fa, diventa *semi-sveglia* e non può usare reazioni o azioni leggendarie. Se era già *semi-sveglia*, si sveglia."

# AZIONI IN COMBATTIMENTO (Attacchi, Soffi, Magie ad azione singola)
actions:
  - name: Attacco Telecinetico
    desc: "Attacco con arma a distanza: +5 al colpire, portata 36 m, un bersaglio. Colpito: 14 (2d10 + 3) danni contundenti."
  - name: Incantesimi
    desc: "A volontà: [[Mage Hand]], [[Prestidigitation]].<br>1/g (ciascuna): [[Mage Armor]] (inclusa in CA), [[Thunderwave]]"
    
bonus_actions:
  - name: Riparazione Telecinetica
    desc: "Carla sceglie una creatura Costrutto entro 15 m da lei che può sentire. Quella cratura recupera il 25% dei suoi HP massimi."

# REAZIONI (Se il mostro non ne ha, cancella questa sezione)
reactions:
  - name: Shield
    desc: "Come l'incantesimo [[Shield]]."

# AZIONI LEGGENDARIE (Rimuovi l'intera sezione per mostri normali)
legendary_actions:
  - name: Presa Telecinetica
    desc: "Carla sceglie un'altra creatura entro 30 m che pesi meno di 180 kg che deve effettuare un TS Forza CD 12. Se fallisce il tiro, la trascina verso di sé di 24 m."