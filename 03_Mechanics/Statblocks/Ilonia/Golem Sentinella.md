```statblock
name: Golem Sentinella
size: Medio
type: Costrutto # Non morto, Bestia, Aberrazione, ecc.
subtype: Golem
alignment: Vero Neutrale
ac: 12
hp: 36
hit_dice: 4d8 + 16
speed: 9 m

# Forza, Destrezza, Costituzione, Intelligenza, Saggezza, Carisma
stats: [14, 12, 18, 3, 8, 1]

# Resistenze, Immunità e Vulnerabilità (Rimuovi o lascia vuoto se non presenti)
damage_vulnerabilities: fulmine
damage_resistances: tagliente, freddo
damage_immunities: veleno, psichico
condition_immunities: accecato, affascinato, assordato, esausto, spaventato, paralizzato, pietrificato, avvelenato

# Sensi e Linguaggi
senses: vista cieca 18 m, percezione passiva 9
languages: Comune (non può parlare)
cr: 1 # Grado di Sfida (puoi usare anche frazioni come 1/2, 1/4, 1/8)

# TRATTI E ABILITÀ PASSIVE (es. Tattiche del Branco, Incantesimi Silenti, ecc.)
traits:
  - name: Arma Primaria
    desc: "Descrizione del funzionamento del tratto passivo. Se inserisci tiri di dado come 1d6 o +5 per colpire tra le virgolette, diventeranno cliccabili se usi il plugin Dice Roller."
  - name: Nome del Secondo Tratto
    desc: "Descrizione del secondo tratto."
    

# AZIONI IN COMBATTIMENTO (Attacchi, Soffi, Magie ad azione singola)
actions:
  - name: Arma Primaria
    desc: "Attacco con arma da mischia: +5 al colpire, portata 1.5 m, un bersaglio. Colpito: 8 (1d12 + 2) danni taglienti/contundenti/perforanti."
  - name: Arco Secondaria
    desc: "Attacco con arma a distanza: +5 al colpire, gittata 24/96 m, un bersaglio. Colpito: 5 (1d6 + 2) danni perforanti."

# REAZIONI (Se il mostro non ne ha, cancella questa sezione)
reactions:
  - name: Schivata Prodigiosa
    desc: "Quando un attaccante che il mostro può vedere lo colpisce con un attacco, il mostro può usare la sua reazione per dimezzare i danni dell'attacco."

