```statblock
name: Kageoni Orochi Consacrato
size: Enorme
type: Aberrazione
alignment: Caotico Malvagio
ac: 13
hp: 105
hit_dice: 10d12 + 40
speed: 12 m

stats: [20, 12, 20, 4, 10, 14]

saves:
  - carisma: +6
  - costituzione: +9

skillsaves:
  - intimidire: +6
  - percezione: +8

damage_vulnerabilities: fuoco
damage_resistances: freddo
damage_immunities: veleno, radiante
condition_immunities: avvelenato, affascinato, spaventato, stordito
senses: scurovisione 24 m, percezione passiva 18
languages: Kageoni
cr: 9

traits:
  - name: Teste Multiple
    desc: "Il Kageoni Orochi ha 5 teste. Ogni volta che il Kageoni Orochi subisce 20 danni in un singolo turno, una delle sue teste muore. Il Kageoni Orochi muore se tutte le sue teste muoiono."
  - name: Teste Reattive
    desc: "Per ogni testa che il Kageoni Orochi ha oltre la prima, ha una Reazione extra da usare come Attacco di Opportunità."
  - name: Furia Folle
    desc: "Ottiene Vantaggio a tutti gli attacchi, ma anche gli attacchi contro di lui hanno vantaggio."
  - name: Aura di Luce Corrotta
    desc: "Il corpo del Kageoni emana bagliori accecanti e oscuri. Qualsiasi creatura che inizia il proprio turno entro 3 metri da lui subisce 7 (2d6) danni necrotici e deve superare un tiro salvezza di Carisma con CD 16. Se lo fallisce, subisce 1 fallimento sul tiro salvezza contro morte; se lo supera, ottiene 1 successo. Se accumula 3 successi, diventa immune a questa aura per le successive 24 ore. Se accumula 3 fallimenti, scende istantaneamente a 0 punti ferita. I successi e i fallimenti si azzerano quando il bersaglio termina un riposo breve o lungo."
  - name: Resistenza Leggendaria (3/giorno)
    desc: "Se il Kageoni Orochi Consacrato fallisce un tiro salvezza, può invece scegliere di superarlo."

actions:
  - name: Multiattack
    desc: "Il Kageoni attacca con un numero di attacchi Morso Sacrilego pari al numero di teste che possiede."
  - name: Morso Sacrilego
    desc: "Attacco con arma da mischia: +8 per colpire, portata 3 m, un bersaglio. Colpito: 10 (1d10 + 5) danni perforanti + 4 (1d6) danni necrotici."
  - name: Inno del Dio dei Cieli Solempi (Ricarica 5-6)
    desc: "Tutte le teste intonano un inno folle all'unisono. Ogni creatura entro 9 metri deve effettuare un tiro salvezza su Saggezza con CD 16, subendo 27 (6d8) danni psichici e diventando spaventata fino alla fine del proprio prossimo turno in caso di fallimento, o la metà dei danni senza essere spaventata in caso di successo. Ogni creatura che fallisce il tiro salvezza subisce inoltre 1 fallimento sul tiro salvezza contro morte. Se accumula 3 fallimenti, scende istantaneamente a 0 punti ferita. I successi e i fallimenti si azzerano quando il bersaglio termina un riposo breve o lungo."

lair_actions:
  - name: Creeping Darkness
    desc: "L'oscurità permeata nei recessi del covo del Kageoni Orochi Consacrato evapora dal terreno e dalle pareti. Non essendo più sotto controllo del Kageoni Orochi, appaiono 2 nuvole in posizioni casuali. La nuvola oscura ha raggio 9 m. Il Kageoni Orochi può vedere normalmente attraverso l'area, che è considerata Pesantemente Oscurata per tutti gli altri. Ogni creatura nell'area è considerata Avvelenata. Può essere dispersa da una folata di vento di almeno 30 km/h. L'area dura finché il Kageoni Orochi non muore o finché non usa di nuovo questa azione."