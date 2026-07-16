---
tags:
  - npc
  - npc/importante
luogo: Foresta Immacolata
fazione: Tribù degli Antichi
stato: Vivo
---

# 👤 Klara, Sciamana degli Antichi
Sciamana della [[Tribù degli Antichi]].
I volpidi hanno una sintonia particolare con la magia irradiata dal nodo di Rosalya e alcuni di essi possiedono doti sciamaniche uniche (vedi [[Sciamanismo]]). Klara è una di questi individui, nata con l'abilità unica di alterare la sua forma.
Fin da piccola è stata curiosa della vita degli umani, ammirandoli piuttosto che odiandoli come molti suoi simili. Usando le sue capacità, si è spesso trasformata in uno di loro per vivere la loro vita.
La sua fedeltà però rimane con la sua tribù, che rifornisce costantemente di risorse attraverso i suoi viaggi nelle cittadine gloriane ed elizhiane.

### 📌 Aspetto e Personalità
- **Tratto Distintivo:** Volpide femmina che parla un perfetto Comune.
- **Voce/Modo di fare:** Accogliente, sorridente e calma. Parla con una dizione perfetta.
- **Obiettivo/Segreto:** Il bene della sua tribù.

### 🔗 Relazioni
- **Alleato di:** [[Ktarr, Capotribù degli Antichi]]
- **In conflitto con:** [[]]
- **Familiari**:
	- [[Fla, Emotista Kemono]] (fratello)
- **Note personali:** 

### ⚔️ Statistiche e Combattimento

```statblock
name: Klara, Sciamana degli Antichi
size: Medio # Minuscolo, Piccolo, Medio, Grande, Enorme, Mastodontico
type: Umanoide # Non morto, Bestia, Aberrazione, ecc.
subtype: Kemono
alignment: Legale Buono
ac: 12
hp: 24
hit_dice: 6d8
speed: 9 m

# Forza, Destrezza, Costituzione, Intelligenza, Saggezza, Carisma
stats: [8, 14, 10, 10, 16, 14]

# Tiri Salvezza (Rimuovi le righe che non servono)
saves:
  - int: 3

# Abilità (Rimuovi le righe che non servono)
skillsaves:
  - intuizione: 5
  - indagare: 2
  - percezione: 5
  - persuasione: 4
  - ingannare: 4

# Sensi e Linguaggi
senses: scurovisione 18 m, percezione passiva 14
languages: Comune, Tribale Kemono, Silvano
cr: 1 # Grado di Sfida (puoi usare anche frazioni come 1/2, 1/4, 1/8)

# TRATTI E ABILITÀ PASSIVE (es. Tattiche del Branco, Incantesimi Silenti, ecc.)
traits:
  - name: Pack Tactics
    desc: "Vantaggio a colpire se un alleato non incapacitato è entro 1,5 m dal bersaglio."

# AZIONI IN COMBATTIMENTO (Attacchi, Soffi, Magie ad azione singola)
actions:
  - name: Fox Fire
    desc: "Attacco magico a distanza: +5 al colpire, gittata 12 m, un bersaglio. Colpito: 5 (1d6 + 1) danni da fuoco. Il bersaglio deve superare un tiro salvezza di Saggezza con CD 13 o rimanere affascinato da Klara fino alla fine del prossimo turno di Klara."
  - name: [[Disguise Self]]
    desc: "Klara lancia l'incantesimo Camuffare se Stesso senza consumare slot incantesimo, usando la Saggezza come caratteristica da incantatore."

# REAZIONI (Se il mostro non ne ha, cancella questa sezione)
reactions:
  - name: Scudo Magico (Ricarica 5-6)
    desc: "Quando la creatura è vittima di un attacco, può aggiungere +4 alla sua AC fino all'inizio del suo prossimo turno."
