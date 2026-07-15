```statblock
name: Furfante Kemono
size: Medio
type: Umanoide
subtype: Kemono
alignment: Vero Neutrale
ac: 11
hp: 7
hit_dice: 2d8
speed: 9 m

# Forza, Destrezza, Costituzione, Intelligenza, Saggezza, Carisma
stats: [10, 12, 10, 10, 12, 10]

# Tiri Salvezza (Rimuovi le righe che non servono)
saves:

# Abilità (Rimuovi le righe che non servono)
skillsaves:
  - percezione: 3
  - sopravvivenza: 3

# Sensi e Linguaggi
senses: scurovisione 9 m, percezione passiva 11
languages: Tribale Kemono
cr: 1/8 # Grado di Sfida (puoi usare anche frazioni come 1/2, 1/4, 1/8)

# AZIONI IN COMBATTIMENTO (Attacchi, Soffi, Magie ad azione singola)
actions:
  - name: Attacco
    desc: "Attacco con arma da mischia: +3 al colpire, portata 1.5 m, un bersaglio. Colpito: 4 (1d6 + 1) danni taglienti, perforanti o contundenti."

# REAZIONI (Se il mostro non ne ha, cancella questa sezione)
reactions:
  - name: Nimble
    desc: "Si allontana senza subire l'attacco che lo avrebbe colpito"
