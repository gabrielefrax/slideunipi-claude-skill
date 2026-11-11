---
name: slide-stile-unipi
description: Crea o adatta presentazioni nello stile ufficiale UniPI (Università di Pisa) partendo dai layout in questa repository. Usala per slide, deck o presentazioni "in stile UniPI".
---

# Slide in stile UniPI

Rispondi in italiano, in modo breve. Il deck è un artifact di tipo Slides (chiama prima `list_types`).

## Metodo

1. Cerca la cartella `slides/` e `deck.json` del template (repository o cartella fornita dall'utente) e leggi solo i layout che servono. Non ridisegnarli da zero.
2. Crea un nuovo artifact Slides e ricopia quei layout in `project/slides/<id>.html`, sostituendo i testi segnaposto (Lorem ipsum, "Nome Cognome", "Innovazione nella Didattica") col contenuto dell'utente. Mantieni posizioni, dimensioni e colori.
3. Immagini: i file usano percorsi `assets/<nome>`. Caricali nell'artifact (`upload_asset`) e sostituisci ogni percorso con l'`/_blob/<id>` restituito. Se una foto manca, chiedila o togli l'immagine: non inventarne.
4. Aggiorna `deck.json` (`order`, `cover`, `sections`) e rinumera il numero di pagina in basso a destra.
5. Per un ritocco a un deck già fatto usa `edit_version` sul singolo file.

## Layout

cover-foto, cover-foto-due-nomi, cover, sezione-foto, sezione, testo-chiaro-griglia, testo-chiaro, testo-scuro-griglia, testo-scuro, testo-semplice-chiaro, testo-semplice-scuro, elenco-chiaro, elenco-scuro, indice, testo-immagine-a, testo-immagine-b, immagini-1, immagini-2, immagini-3, tabella, team, contatti-foto, chiusura. Usa solo quelli necessari.

## Regole di stile

- Canvas 1920×1080, solo stili inline, elementi con `position:absolute`.
- Colori: Primary #225DD7, Secondary #1A315D, Support #F0F0F0, titoli su chiaro #003D7C; testo nero su chiaro, bianco su scuro.
- Font: Inter per i titoli (64px bold, interlinea 70px; 128px nelle cover), Titillium Web per testi (sottotitolo 36px bold, corpo 26–28px).
- Margine sinistro circa 140px, titolo in alto a sinistra (top 110px). Titoli senza nulla a destra: larghezza 1640px, una riga; accanto a immagini o colonne restano più stretti.
- Nessun footer: solo il numero di pagina (24px, 600, left 1556, top 1008, larghezza 300, a destra; Primary su chiaro, bianco su scuro).
- Logo bianco su fondi scuri o foto con velatura blu; non ricolorarlo né deformarlo.

## Limiti noti

Tabella con linee verticali visibili e senza filetto blu su TOTALE; icone contatti dell'editor; foto della slide team da sostituire; non è il PowerPoint ufficiale.
