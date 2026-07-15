```statblock
name: Guerriero Kemono
size: Medio
type: Umanoide # Non morto, Bestia, Aberrazione, ecc.
subtype: Kemono
alignment: Vero Neutrale
ac: 12 (armatura di cuoio)
hp: 16
hit_dice: 4d8 + 4
speed: 9 m

# Forza, Destrezza, Costituzione, Intelligenza, Saggezza, Carisma
stats: [14, 12, 12, 10, 10, 10]

# Tiri Salvezza (Rimuovi le righe che non servono)
saves:
  - forza: 4

# Abilità (Rimuovi le righe che non servono)
skillsaves:
  - intimidire: 2
  - sopravvivenza: 2

# Sensi e Linguaggi
senses: scurovisione 9 m, percezione passiva 10
languages: Tribale Kemono
cr: 1/2 # Grado di Sfida (puoi usare anche frazioni come 1/2, 1/4, 1/8)

# TRATTI E ABILITÀ PASSIVE (es. Tattiche del Branco, Incantesimi Silenti, ecc.)
traits:
  - name: Pack Tactics
    desc: "Vantaggio a colpire se un alleato non incapacitato è entro 1,5 m dal bersaglio."

# AZIONI IN COMBATTIMENTO (Attacchi, Soffi, Magie ad azione singola)
actions:
  - name: Attacco
    desc: "Attacco con arma da mischia: +2 al colpire, portata 1.5 m, un bersaglio. Colpito: 8 (1d12 + 2) danni taglienti, perforanti o contundenti."
bonus_actions:
  - name: Shout Orders (Ricarica 4)
    desc: "Fino a 6 alleati che possono udire il guerriero possono effettuare il loro movimento o un'azione a loro scelta."

# REAZIONI (Se il mostro non ne ha, cancella questa sezione)
reactions:

