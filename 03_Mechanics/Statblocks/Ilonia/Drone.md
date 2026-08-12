```statblock
name: Drone
size: Medio
type: Costrutto
subtype: Golem
alignment: Vero Neutrale
ac: 11
hp: 9
hit_dice: 1d8 + 4
speed: 12 m

# Forza, Destrezza, Costituzione, Intelligenza, Saggezza, Carisma
stats: [12, 10, 18, 3, 8, 1]

# Resistenze, Immunità e Vulnerabilità (Rimuovi o lascia vuoto se non presenti)
damage_vulnerabilities: fulmine
damage_immunities: veleno, psichico
condition_immunities: accecato, affascinato, assordato, esausto, spaventato, paralizzato, pietrificato, avvelenato

# Sensi e Linguaggi
senses: vista cieca 18 m, percezione passiva 9
languages: Comune (non può parlare)
cr: 1/8 # Grado di Sfida (puoi usare anche frazioni come 1/2, 1/4, 1/8)

# AZIONI IN COMBATTIMENTO (Attacchi, Soffi, Magie ad azione singola)
actions:
  - name: Schianto
    desc: "Attacco con arma da mischia: +3 al colpire, portata 1.5 m, un bersaglio. Colpito: 4 (1d6 + 1) danni contundenti."

