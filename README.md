# Template slide stile UniPI

Layout per presentazioni nello stile dell'immagine coordinata dell'Università di Pisa (manuale "UNIPI Brand style guide", pp. 30–40), pensati per gli artifact **Slides** di Claude. Non è il file PowerPoint ufficiale: è una riproduzione a mano dei suoi layout.

## Contenuto

| Percorso | Cosa c'è |
|---|---|
| `slides/*.html` | Un file per slide (23 layout), canvas 1920×1080, stili inline |
| `deck.json` | Ordine delle slide, sezioni e font (Inter, Titillium Web) |
| `assets/` | Logo UniPI bianco. Le foto vanno aggiunte (vedi `assets/FOTO.md`) |
| `skill/slide-stile-unipi/SKILL.md` | Skill per Claude: crea un deck partendo da questi layout |

## Layout

cover-foto, cover-foto-due-nomi, cover, sezione-foto, sezione, testo-chiaro-griglia, testo-chiaro, testo-scuro-griglia, testo-scuro, testo-semplice-chiaro, testo-semplice-scuro, elenco-chiaro, elenco-scuro, indice, testo-immagine-a, testo-immagine-b, immagini-1, immagini-2, immagini-3, tabella, team, contatti-foto, chiusura.

## Come usarlo

1. Scarica o clona la repository.
2. Installa la skill: copia `skill/slide-stile-unipi/` tra le tue skill di Claude.
3. Chiedi a Claude, per esempio: *"Fammi una presentazione in stile UniPI su … con queste slide: copertina, indice, tre pagine di testo, chiusura"*, allegando o indicando la cartella `slides/` e `assets/`.
4. Claude crea un nuovo artifact Slides, carica logo e foto e sostituisce i testi segnaposto.

Senza Claude: i file `slides/*.html` sono HTML semplice con posizioni assolute, leggibile e modificabile a mano; le immagini sono riferite come `assets/<nome>`.

## Regole di stile (sintesi)

- Colori: Primary `#225DD7`, Secondary `#1A315D`, Support `#F0F0F0`; titoli su chiaro `#003D7C`.
- Font: Inter (titoli), Titillium Web (testi).
- Nessun footer: solo il numero di pagina in basso a destra.
- Titoli senza nulla a destra: larghezza 1640 px, una riga.

## Limiti noti

- La tabella mostra le linee verticali della griglia e non ha il filetto blu sopra TOTALE (limite dell'editor Slides).
- Le icone della slide contatti sono quelle dell'editor, non quelle ufficiali.
- Le foto della slide `team` sono ritagli di una foto di gruppo: vanno sostituite.
- Il logo e le foto sono materiale dell'Università di Pisa: usare nel rispetto del manuale di identità visiva e dei suoi termini d'uso. Nessuna licenza è concessa su questi contenuti.
