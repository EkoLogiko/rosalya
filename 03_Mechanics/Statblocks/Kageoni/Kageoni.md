```statblock
name: Kageoni
size: Medio # Minuscolo, Piccolo, Medio, Grande, Enorme, Mastodontico
type: Aberrazione # Non morto, Bestia, Aberrazione, ecc.
subtype: (qualsiasi sottotipo, es. goblinoidi)
alignment: Legale Malvagio
ac: 10 (naturale)
hp: 22
hit_dice: 4d8 + 4
speed: 9 m

# Forza, Destrezza, Costituzione, Intelligenza, Saggezza, Carisma
stats: [10, 12, 10, 12, 10, 14]

# Tiri Salvezza (Rimuovi le righe che non servono)
saves:
  - carisma: 4

# Abilità (Rimuovi le righe che non servono)
skillsaves:
  - arcano: 3
  - furtività: 5

# Resistenze, Immunità e Vulnerabilità (Rimuovi o lascia vuoto se non presenti)
damage_vulnerabilities: fuoco
damage_resistances: freddo
damage_immunities: veleno
condition_immunities: avvelenato, affascinato

# Sensi e Linguaggi
senses: scurovisione 24 m, percezione passiva 10
languages: Kageoni
cr: 1/2 # Grado di Sfida (puoi usare anche frazioni come 1/2, 1/4, 1/8)

# TRATTI E ABILITÀ PASSIVE (es. Tattiche del Branco, Incantesimi Silenti, ecc.)
traits:
  - name: Distracting Attack
    desc: "Dopo aver colpito un nemico con un attacco, può diventare invisibile fino all'inizio del suo prossimo turno."

# AZIONI IN COMBATTIMENTO (Attacchi, Soffi, Magie ad azione singola)
actions:
  - name: Artiglio Oscuro
    desc: "Attacco con arma da mischia: +4 al colpire, portata 1.5 m, un bersaglio. Colpito: 8 (1d12 + 2) danni taglienti."
    
bonus_actions:
  - name: Withering Blow
    desc: "Se il prossimo Artiglio Oscuro colpisce, il bersaglio subisce 5 danni all'inizio di ognuno dei suoi turni. Il bersaglio può effettuare un Tiro Salvezza COS 10 alla fine di ogni suoi turno per terminare l'effetto. L'effetto termina anche se la creatura muore o viene distrutta."

