```statblock
name: Kageoni Consacrato
size: Medio
type: Aberrazione
alignment: Legale Malvagio
ac: 11 (naturale)
hp: 38 (7d8 + 7)
speed: 9 m

# Modificata la Costituzione a 12 per giustificare i +7 HP e rendere il mostro più solido
stats: [8, 12, 12, 14, 10, 16] 

saves:
  - carisma: +5

skillsaves:
  - arcano: +4
  - intimidire: +5
  - furtività: +3

damage_vulnerabilities: fuoco
damage_resistances: freddo
damage_immunities: veleno
condition_immunities: avvelenato, affascinato
senses: scurovisione 24 m, percezione passiva 10
languages: Kageoni
cr: 3

traits:
  - name: Aura of Destruction
    desc: "Un nemico che termina il suo turno entro 1,5 metri dal Kageoni deve superare un tiro salvezza di Carisma con CD 13. Se lo fallisce, subisce 1 fallimento sul tiro salvezza contro morte; se lo supera, ottiene 1 successo. Se accumula 3 successi, diventa immune a questa aura per le successive 24 ore. Se accumula 3 fallimenti, scende istantaneamente a 0 punti ferita. I successi e i fallimenti si azzerano quando il bersaglio termina un riposo breve o lungo."
  
  - name: Fanatismo
    desc: "Finché il Kageoni ha meno della metà dei suoi punti ferita massimi (19 o meno), subisce solo la metà di qualsiasi danno che riceve, e l'altra metà viene trasferita a un alleato consenziente entro 1,5 metri da lui. Inoltre, finché questa condizione è attiva, tutti gli alleati del Kageoni entro 9 metri hanno vantaggio ai tiri per colpire."

actions:
  - name: Multiattack
    desc: "Il Kageoni effettua due attacchi con l'Artiglio Oscuro."
  
  - name: Artiglio Oscuro
    desc: "Attacco con arma da mischia: +3 per colpire, portata 1,5 m, un bersaglio. Colpito: 8 (1d10 + 3) danni da forza. Se l'attacco va a segno, il Kageoni può scegliere di diventare invisibile fino all'inizio del suo turno successivo o finché non attacca o lancia un incantesimo."

bonus_actions:
  - name: Heal Ally (Ricarica 5-6)
    desc: "Il Kageoni sussurra parole oscure. Un alleato Kageoni entro 15 metri che possa sentirlo recupera 10 (2d6 + 3) punti ferita."