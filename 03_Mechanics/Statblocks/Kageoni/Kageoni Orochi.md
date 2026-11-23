```statblock
name: Kageoni Orochi
size: Enorme
type: Aberrazione
alignment: Legale Malvagio
ac: 15
hp: 136 (16d12 + 80)
speed: 12 m

stats: [20, 12, 20, 16, 10, 14] 

saves:
  - carisma: +6

skillsaves:
  - arcano: +4
  - intimidire: +5
  - furtività: +3
  - percezione: +6

damage_vulnerabilities: fuoco
damage_resistances: freddo
damage_immunities: veleno
condition_immunities: avvelenato, affascinato
senses: scurovisione 24 m, percezione passiva 16
languages: Kageoni
cr: 9

traits:
  - name: Teste Multiple
    desc: "Il Kageoni Orochi ha 8 teste. Ogni volta che il Kageoni Orochi subisce 20 danni in un singolo turno, una delle sue teste muore. Il Kageoni Orochi muore se tutte le sue teste muoiono. Alla fine di ogni suo turno dove ha almeno una testa viva, il Kageoni Orochi rigenera una delle sue teste, a mano che non abbia subito danni da Fuoco dal suo ultimo turno. Ogni volta che rigenera una testa, recupera 15 HP."
  
  - name: Teste Reattive
    desc: "Per ogni testa che il Kageoni Orochi ha oltre la prima, ha una Reazione extra da usare come Attacco di Opportunità."
    
  - name: Divoratore del Sole
    desc: "Al posto di effettuare un attacco con una testa, il Kageoni Orochi può divorare la Luce Divina di Kiseki, se ne ha una fonte entro 30m. Ogni volta che lo fa, guadagna 1 carica di Luce Divina. Il Kageoni Orochi effettua questa azione un numero casuale di volte per turno, fino al numero di sue teste attive - 1."
    
  - name: Resistenza Leggendaria (3/giorno)

actions:
  - name: Multiattack
    desc: "Il Kageoni attacca con un numero di attacchi Morso Oscuro pari al numero di teste che possiede."
  
  - name: Morso Oscuro
    desc: "Attacco con arma da mischia: +8 per colpire, portata 3 m, un bersaglio. Colpito: 10 (1d10 + 5) danni perforanti."
    
  - name: Soffio Solare
    desc: "Utilizzabile solo se ha almeno 10 cariche di Luce Divina."
