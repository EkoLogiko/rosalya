---
tags:
  - npc
  - npc/one-shot
luogo: Foresta Immacolata
fazione: Tribù degli Antichi
stato: Vivo
specie: Kemono
---

# 👤 Fla, Emotista Kemono
Il Kemono scelto dall'Ars Passionum.
Scacciato dalla [[Tribù degli Antichi]] poiché scelto dall'[[Ars Passionum]] e ritenuto un problema per la sopravvivenza dell'insediamento.

### 📌 Aspetto e Personalità
- **Tratto Distintivo:** Volpide dalla coda spezzata.
- **Voce/Modo di fare:** Voce effemminata; delicato, romantico e vagamente codardo.
- **Obiettivo/Segreto:** Desidera reclamare il suo posto a Gloria come membro della [[Wisdom]], divenendo il primo e più grande Kemono mago della storia.

### 🔗 Relazioni
- **Alleato di:** [[Amica di Fla]]
- **In conflitto con:** [[Tribù degli Antichi]]
- **Note personali:** 

### ⚔️ Statistiche e Combattimento

```statblock
name: Fla
size: Medio # Minuscolo, Piccolo, Medio, Grande, Enorme, Mastodontico
type: Umanoide # Non morto, Bestia, Aberrazione, ecc.
subtype: Kemono
alignment: Caotico Buono
ac: 13 (naturale)
hp: 45
hit_dice: 7d8 + 14
speed: 9 m

# Forza, Destrezza, Costituzione, Intelligenza, Saggezza, Carisma
stats: [10, 16, 14, 8, 12, 10]

# Tiri Salvezza (Rimuovi le righe che non servono)
saves:
  - destrezza: 5

# Abilità (Rimuovi le righe che non servono)
skillsaves:
  - acrobazia: 5
  - intuizione: 3
  - addestrare animali: 3

# Resistenze, Immunità e Vulnerabilità (Rimuovi o lascia vuoto se non presenti)
condition_immunities: affascinato

# Sensi e Linguaggi
senses: scurovisione 9 m, percezione passiva 11
languages: Tribale Kemono, Silvano
cr: 2 # Grado di Sfida (puoi usare anche frazioni come 1/2, 1/4, 1/8)

# TRATTI E ABILITÀ PASSIVE (es. Tattiche del Branco, Incantesimi Silenti, ecc.)
traits:
  - name: Magic Resistance
    desc: "Ha vantaggio ai tiri salvezza contro le magie e altri effetti magici."
  - name: Pack Tactics
    desc: "Vantaggio a colpire se un alleato non incapacitato è entro 1,5 m dal bersaglio."

# AZIONI IN COMBATTIMENTO (Attacchi, Soffi, Magie ad azione singola)
actions:
  - name: Multiattack
    desc: "Fla effettua due attacchi."
  - name: Attacco
    desc: "Attacco a mani nude: +5 al colpire, gittata 1,5 m, un bersaglio. Colpito: 9 (1d12 + 3) danni taglienti o perforanti."

# REAZIONI (Se il mostro non ne ha, cancella questa sezione)
reactions:
  - name: Retailation
    desc: "Quando viene colpito da un attacco, può attaccare la creatura che l'ha colpito."