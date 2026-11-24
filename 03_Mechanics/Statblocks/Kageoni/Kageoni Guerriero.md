```statblock
name: Kageoni Guerriero
size: Medio 
type: Aberrazione 
alignment: Legale Malvagio 
ac: 13 (armatura naturale) 
hp: 52 
hit_dice: 8d8 + 16 
speed: 9 m 
stats: [10, 16, 14, 12, 10, 14] 
saves: 
- destrezza: 5 
- carisma: 4 

skillsaves: 
- arcano: 3 
- furtività: 7 
  
damage_vulnerabilities: fuoco 
damage_resistances: freddo 
damage_immunities: veleno 
condition_immunities: avvelenato, affascinato 
senses: scurovisione 24 m, percezione passiva 10 
languages: Kageoni 
cr: 2 
traits:
- name: Distracting Attack 
  desc: "Una volta per turno, dopo aver colpito una creatura con un attacco in mischia, il Kageoni può diventare invisibile fino all'inizio del suo prossimo turno o finché non attacca o lancia un incantesimo." 
actions: 
- name: Multiattacco 
  desc: "Il Kageoni effettua due attacchi con Artiglio Oscuro." 
- name: Artiglio Oscuro 
  desc: "Attacco con arma da mischia: +5 al colpire, portata 1,5 m, un bersaglio. Colpito: 8 (1d10 + 3) danni taglienti." 
bonus_actions: 
- name: Withering Blow 
  desc: "Se il prossimo attacco con Artiglio Oscuro effettuato dal Kageoni in questo turno colpisce, il bersaglio è avvizzito dall'ombra. Finché l'effetto persiste, il bersaglio subisce 5 (1d10) danni necrotici all'inizio di ogni suo turno. Il bersaglio può ripetere il tiro salvezza su Costituzione con CD 12 alla fine di ogni suo turno, terminando l'effetto su di sé in caso di successo. Effetti multipli non si sommano e l'effetto termina immediatamente se il Kageoni muore."

