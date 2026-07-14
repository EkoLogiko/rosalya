```statblock
name: Amica di Fla (Manticora)
size: Grande
type: Mostruosità
alignment: Legale Malvagio
ac: 14 (Armatura Naturale)
hp: 68
hit_dice: 8d10 + 24
speed: 9 m, volare 15 m
stats: [17, 16, 17, 7, 12, 8]
senses: scurovisione 18 m, percezione passiva 11
languages: Comune
cr: 3

traits:
  - name: Ricrescita degli Aculei della Coda
    desc: "La manticora possiede ventiquattro aculei sulla coda. Gli aculei utilizzati ricrescono quando la manticora completa un riposo lungo."

actions:
  - name: Multiattacco
    desc: "La manticora effettua tre attacchi di Morso o Aculeo della Coda in qualsiasi combinazione."
  - name: Morso
    desc: "Attacco con arma da mischia: +5 al colpire, portata 1.5 m, un bersaglio. Colpito: 7 (1d8 + 3) danni perforanti."
  - name: Aculeo della Coda
    desc: "Attacco con arma a distanza: +5 al colpire, gittata 30/60 m, un bersaglio. Colpito: 7 (1d8 + 3) danni perforanti."

lair_actions:
  - name: Crollo di Detriti
    desc: "La manticora sbatte violentemente le ali contro le pareti rocciose della sua tana. Una pioggia di pietre cade in un punto a scelta entro 18 metri. Ogni creatura in quell'area da 3 metri di raggio deve superare un TS di Destrezza CD 13 o subire 7 (2d6) danni d'impatto ed essere buttata a terra prona."
  - name: Ars Passionum
    desc: "L'Ars Passionum lancia un incantesimo emotivo di una certa natura su tutte le creature che ne subiscono gli effetti se non superano un TS di Saggezza CD 12. Essendo da un po' di tempo sotto l'effetto dell'Ars Passionum, l'Amica di Fla ha vantaggio nel resistere a questa prova.<br/>*Rabbia*: Il personaggio usa la Reazione per attaccare un alleato o sé stesso, se non ha alleati entro gittata.<br/>*Paura*: Il personaggio ha la condizione Spaventato rispetto all'Ars Passionum.<br/>*Tristezza*: Il personaggio cade Prono e usa la sua azione per piangere in questo turno."