```statblock
name: Capolavoro di Carla
size: Enorme
type: Costrutto
subtype: Golem
alignment: Vero Neutrale
modifier: 3
ac: 15
hp: 74
hit_dice: 9d8 + 36
speed: 6 m

# Forza, Destrezza, Costituzione, Intelligenza, Saggezza, Carisma
stats: [18, 8, 18, 3, 8, 1]

# Resistenze, Immunità e Vulnerabilità (Rimuovi o lascia vuoto se non presenti)
damage_vulnerabilities: fulmine
damage_resistances: tagliente, perforante, freddo
damage_immunities: veleno, psichico
condition_immunities: accecato, affascinato, assordato, esausto, spaventato, paralizzato, pietrificato, avvelenato

# Sensi e Linguaggi
senses: vista cieca 18 m, percezione passiva 9
languages: Comune (non può parlare)
cr: 3 # Grado di Sfida (puoi usare anche frazioni come 1/2, 1/4, 1/8)

# TRATTI E ABILITÀ PASSIVE (es. Tattiche del Branco, Incantesimi Silenti, ecc.)
traits:
  - name: Placche Metalliche
    desc: "+2 alla CA. Questo bonus si riduce a +1 se il Capolavoro di Carla ha meno del 75% dei suoi HP massimi, a 0 se ha meno del 50% e a -1 se ha meno del 25%."
  - name: Sentinella
    desc: "Il Capolavoro di Carla effettua attacchi d'opportunità senza usare Reazioni."
  - name: Protettore
    desc: "Gli attacchi effettuati verso Carla hanno svantaggio finché il Capolvoro è attivo."

# AZIONI IN COMBATTIMENTO (Attacchi, Soffi, Magie ad azione singola)
actions:
  - name: Multiattacco
    desc: "Il Capolavoro effettua una quasiasi combinazione di 2 attacchi Schianto o Mitragliatori Arcani. Se ha usato *Sovraccarico*, ne effettua 3."
  - name: Schianto
    desc: "Attacco con arma da maschia: +5 al colpire, portata 3 m, un bersaglio. Colpito: 12 (2d8 + 4) danni contundenti."
  - name: Mitragliatori Arcani
    desc: "Attacco con arma a distanza: +5 al colpire, gittata 24/96 m, un bersaglio. Colpito: 10 (1d12 + 4) danni da fuoco/freddo/acido/fulmine."
  - name: Scarica Totale
    desc: "Utilizzabile solamente se gli HP sono inferiori al 50% degli HP massimi. Tutte le creature che non sono a bordo del Capolavoro devono effettuare un TS Destrezza con CD 12. Se falliscono, subiscono 24 (4d8 + 8) danni di un tipo casuale tra fuoco/freddo/acido/fulmine, altrimenti ne subiscono la metà. Il Capolavoro non può più usare questo attacco o attacchi di *Mitragliatori Arcani* dopo aver utilizzato questo attacco."
    
bonus_actions:
  - name: Sovraccarico (Ricarica 5-6)
    desc: "Il Capolavoro di Carla effettua un'azione di *Scatto* o di *Disingaggiare*."

