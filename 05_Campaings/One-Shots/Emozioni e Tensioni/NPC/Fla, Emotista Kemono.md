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
È dotato di capacità sciamaniche legate alle emozioni, che lo hanno portato a essere il candidato dell'[[Ars Passionum]].

### 📌 Aspetto e Personalità
- **Tratto Distintivo:** Volpide dalla coda spezzata.
- **Voce/Modo di fare:** Voce effemminata; delicato, romantico e vagamente codardo.
- **Obiettivo/Segreto:** Desidera reclamare il suo posto a Gloria come membro della [[Wisdom]], divenendo il primo e più grande Kemono mago della storia.

### 🔗 Relazioni
- **Alleato di:** [[Amica di Fla]]
- **In conflitto con:** [[Tribù degli Antichi]]
- **Familiari**:
	- [[Klara, Sciamana degli Antichi]] (sorella)
- **Note personali:** 

### ⚔️ Statistiche e Combattimento

```statblock
name: Fla
size: Medio # Minuscolo, Piccolo, Medio, Grande, Enorme, Mastodontico
type: Umanoide # Non morto, Bestia, Aberrazione, ecc.
subtype: Kemono
alignment: Caotico Buono
ac: 12
hp: 25
hit_dice: 6d8
speed: 9 m

# Forza, Destrezza, Costituzione, Intelligenza, Saggezza, Carisma
stats: [10, 15, 10, 14, 12, 16]

# Tiri Salvezza (Rimuovi le righe che non servono)
saves:
  - str: 0
  - dex: 4
  - con: 0
  - int: 1
  - wis: 2
  - cha: 3

# Abilità (Rimuovi le righe che non servono)
skillsaves:
  - acrobazia: 5
  - intuizione: 3
  - addestrare animali: 3
  - percezione: 3

# Resistenze, Immunità e Vulnerabilità (Rimuovi o lascia vuoto se non presenti)
condition_immunities: affascinato

# Sensi e Linguaggi
senses: scurovisione 9 m, percezione passiva 13
languages: Tribale Kemono, Silvano
cr: 1 # Grado di Sfida (puoi usare anche frazioni come 1/2, 1/4, 1/8)

# TRATTI E ABILITÀ PASSIVE (es. Tattiche del Branco, Incantesimi Silenti, ecc.)
traits:
  - name: Magic Resistance
    desc: "Ha vantaggio ai tiri salvezza contro le magie e altri effetti magici."
  - name: Pack Tactics
    desc: "Vantaggio a colpire se un alleato non incapacitato è entro 1,5 m dal bersaglio."

# AZIONI IN COMBATTIMENTO (Attacchi, Soffi, Magie ad azione singola)
actions:
  - name: Attacco
    desc: "Attacco a mani nude: +5 al colpire, gittata 1,5 m, un bersaglio. Colpito: 4 (1d6) danni taglienti o perforanti."
  - name: Mind Sliver (Ricarica 4-5-6)
    desc: "Intensimo a distanza: gittata 30 m, un bersaglio. TS INT 12: 7 (2d6) danni psichici e 1d4 in meno al prossimo TS."
  - name: Mind Sliver (Ricarica 6)
    desc: "Intensimo a distanza: gittata 30 m, un bersaglio. TS INT 12: 7 (2d6) danni psichici e 1d4 in meno al prossimo TS."
  - name: [[Calm Emotions]] (Ricarica 6)
    desc: "Come il relativo incantesimo."