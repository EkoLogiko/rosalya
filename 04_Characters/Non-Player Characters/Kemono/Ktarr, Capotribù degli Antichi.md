---
tags:
  - npc
  - npc/importante
luogo: Foresta Immacolata
fazione: Tribù degli Antichi
stato: Vivo
---

# 👤 Ktarr, Capotribù degli Antichi
Capotribù della [[Tribù degli Antichi]].
Kemono dall'aspetto di una nerboruta pantera ed esperto combattente. Seppur anziano, continua a difendere l'insediamento con ferocia e orgoglio.

### 📌 Aspetto e Personalità
- **Tratto Distintivo:** Enorme uomo-pantera nerboruto.
- **Voce/Modo di fare:** Cupa e tonante; usa poche parole ma molto incisive.
- **Obiettivo/Segreto:** La sopravvivenza della tribù. Spera di riuscire a ottenere un alleanza con Gloria per assicurarsi il futuro del suo popolo contro Yuuhiyoake e la piaga del Mörderkind.

### 🔗 Relazioni
- **Alleato di:** [[Klara, Sciamana degli Antichi]]
- **In conflitto con:** [[Yuuhiyoake]]
- **Note personali:** 

### ⚔️ Statistiche e Combattimento

```statblock
name: Ktarr, Capotribù degli Antichi
size: Grande # Minuscolo, Piccolo, Medio, Grande, Enorme, Mastodontico
type: Umanoide # Non morto, Bestia, Aberrazione, ecc.
subtype: Felinide
alignment: Legale Neutrale
ac: 14 (Armatura di Cuoio Borchiato)
hp: 84
hit_dice: 13d8 + 26
speed: 9 m, scalare 6 m # es. 9 m, volare 18 m, nuotare 9 m

# Forza, Destrezza, Costituzione, Intelligenza, Saggezza, Carisma
stats: [18, 12, 14, 10, 14, 12]

# Tiri Salvezza (Rimuovi le righe che non servono)
saves:
  - destrezza: 3
  - carisma: 3

# Abilità (Rimuovi le righe che non servono)
skillsaves:
  - atletica: 6
  - intimidire: 3
  - natura: 4

# Resistenze, Immunità e Vulnerabilità (Rimuovi o lascia vuoto se non presenti)
damage_resistances: freddo, fulmine
condition_immunities: affascinato, spaventato

# Sensi e Linguaggi
senses: scurovisione 18 m, percezione passiva 13
languages: Tribale Kemono
cr: 4 # Grado di Sfida (puoi usare anche frazioni come 1/2, 1/4, 1/8)

# TRATTI E ABILITÀ PASSIVE (es. Tattiche del Branco, Incantesimi Silenti, ecc.)
traits:
  - name: Pack Tactics
    desc: "Vantaggio a colpire se un alleato non incapacitato è entro 1,5 m dal bersaglio."

# AZIONI IN COMBATTIMENTO (Attacchi, Soffi, Magie ad azione singola)
actions:
  - name: Multiattacco
    desc: "Ktarr effettua un attacco con Ascia da Guerra e uno con la Morningstar."
  - name: Ascia da Guerra
    desc: "Attacco con arma da mischia: +6 al colpire, portata 1.5 m, un bersaglio. Colpito: 13 (2d8 + 4) danni taglienti. Se la creatura colpita è di taglia Grande o meno, ha la condizione *prono*."
  - name: Morningstar
    desc: "Attacco con arma da mischia: +6 al colpire, portata 1.5 m, un bersaglio. Colpito: 13 (2d8 + 4) danni perforanti e la creatura ha svantaggio sul prossimo tiro per colpire che effettua prima della fine del suo prossimo turno."
    
bonus_actions:
  - name: Sfida Avversario (Ricarica 4-6)
    desc: "La prossima volta che questa Ktarr colpisce un bersaglio, oltre all'effetto dell'attacco, esso viene sfidato. Una creatura sfidata ha svantaggio nei tiri per colpire verso ogni altra creatura se non quella che lo ha sfidato. Alla fine di ogni turno, la creatura può fare un TS CHA 12 per terminare l'effetto."

# AZIONI LEGGENDARIE (Rimuovi l'intera sezione per mostri normali)
legendary_actions:
  - name: Scatto Leggendario
    desc: "Il mostro si muove fino alla sua velocità senza provocare attacchi di opportunità."