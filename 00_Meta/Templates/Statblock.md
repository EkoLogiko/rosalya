```statblock
name: Nome del Mostro o NPC
size: Medio # Minuscolo, Piccolo, Medio, Grande, Enorme, Mastodontico
type: Umanoide # Non morto, Bestia, Aberrazione, ecc.
subtype: (qualsiasi sottotipo, es. goblinoidi)
alignment: Neutrale Malvagio
ac: 15 (Armatura di Cuoio Borchiato)
hp: 45
hit_dice: 6d8 + 18
speed: 9 m, scalare 6 m # es. 9 m, volare 18 m, nuotare 9 m

# Forza, Destrezza, Costituzione, Intelligenza, Saggezza, Carisma
stats: [10, 16, 14, 12, 10, 8]

# Tiri Salvezza (Rimuovi le righe che non servono)
saves:
  - destrezza: 5
  - intelligenza: 3

# Abilità (Rimuovi le righe che non servono)
skillsaves:
  - furtività: 5
  - percezione: 2

# Resistenze, Immunità e Vulnerabilità (Rimuovi o lascia vuoto se non presenti)
damage_vulnerabilities: perforante
damage_resistances: freddo, fulmine
damage_immunities: veleno
condition_immunities: avvelenato, affascinato

# Sensi e Linguaggi
senses: scurovisione 18 m, percezione passiva 12
languages: Comune, Silvano
cr: 2 # Grado di Sfida (puoi usare anche frazioni come 1/2, 1/4, 1/8)

# TRATTI E ABILITÀ PASSIVE (es. Tattiche del Branco, Incantesimi Silenti, ecc.)
traits:
  - name: Nome del Primo Tratto
    desc: "Descrizione del funzionamento del tratto passivo. Se inserisci tiri di dado come 1d6 o +5 per colpire tra le virgolette, diventeranno cliccabili se usi il plugin Dice Roller."
  - name: Nome del Secondo Tratto
    desc: "Descrizione del secondo tratto."

# AZIONI IN COMBATTIMENTO (Attacchi, Soffi, Magie ad azione singola)
actions:
  - name: Spada Corta
    desc: "Attacco con arma da mischia: +5 al colpire, portata 1.5 m, un bersaglio. Colpito: 6 (1d6 + 3) danni perforanti."
  - name: Arco Corto
    desc: "Attacco con arma a distanza: +5 al colpire, gittata 24/96 m, un bersaglio. Colpito: 6 (1d6 + 3) danni perforanti."

# REAZIONI (Se il mostro non ne ha, cancella questa sezione)
reactions:
  - name: Schivata Prodigiosa
    desc: "Quando un attaccante che il mostro può vedere lo colpisce con un attacco, il mostro può usare la sua reazione per dimezzare i danni dell'attacco."

# AZIONI LEGGENDARIE (Rimuovi l'intera sezione per mostri normali)
legendary_actions:
  - name: Scatto Leggendario
    desc: "Il mostro si muove fino alla sua velocità senza provocare attacchi di opportunità."

