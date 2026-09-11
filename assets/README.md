# Asset del marchio MetisT

## In uso sul sito

| File | Dove si usa |
|---|---|
| `metist-wordmark.png` | Lockup principale nell'header. 400×107 RGBA con trasparenza reale: lo sfondo bianco dell'originale è stato rimosso perché sull'header, bianco al 96%, spiccava come un rettangolo più chiaro. |
| `metist-mt.svg` | Monogramma MT con riquadro navy: favicon e icona per dispositivi Apple. Il fondo pieno serve a dare massa — a 16px un marchio a tratto sottile non è leggibile. |
| `metist-og.png` | Anteprima per la condivisione sui social (Open Graph, 1200×630). Wordmark bianco→cyan su navy. |

## Per la stampa

| File | Dove si usa |
|---|---|
| `metist-mt-print.png` | **Carta intestata, presentazioni e stampa a colori.** 738×326 RGBA: a 300 dpi copre 62 mm, abbondante per l'A4. Riproduce anche la sfumatura curva interna alla T. |
| `metist-mt-print.svg` | **Insegne, grande formato, ricamo, incisione, tinta unica.** 752 byte, scalabile all'infinito. Ricavato tracciando i contorni del raster: la sagoma è esatta, ma la sfumatura curva dentro la T non c'è, perché è una variazione di colore interna e non un bordo. Per questi usi non serve comunque. |

## Non adottato

| File | Nota |
|---|---|
| `metist-mark.svg` | Ridisegno piatto del simbolo storico (orbita aperta, coda cyan, monogramma μη). Prodotto durante la valutazione e **non adottato**: la scelta è caduta sul monogramma MT. Conservato come alternativa. Da non usare nell'header — porta il lockup a 263px e a 1440px manda il menu a capo — né come favicon, perché sotto i 32px non è leggibile. |

---

Colori di riferimento: blu `#0A46AC`, accento cyan `#0098F0`. Ricavati misurando i pixel del logo originale (tinta 215-218°, saturazione 96-98%).

**Il monogramma MT non è ridisegnato**: la M e la T sono ritagliate dal file del logo originale e ricomposte, così tratti, proporzioni e gradiente sono esattamente quelli del marchio.

Esiste in due forme perché nessuna delle due copre tutti i casi. Il **raster** è fedele al 100%, compresa la sfumatura interna alla T, ma ha una risoluzione finita. Il **vettoriale**, ottenuto tracciando i contorni, scala all'infinito e riproduce la sagoma esattamente, ma appiattisce quella sfumatura interna. Per le lavorazioni che richiedono il vettoriale — insegne, ricamo, incisione, tinta unica — la sfumatura non sarebbe comunque riproducibile, quindi la perdita è teorica.

## Loghi tecnologici

`tech/` contiene i 16 loghi della sezione "Stack tecnologico": SVG del pacchetto simple-icons 11.0.0 (licenza CC0 per il pacchetto), ricolorati nel blu di marchio `#0A46AC`.

Sono ospitati qui invece che caricati da cdn.simpleicons.org perché quel CDN ha rimosso AWS e Azure, e i due riquadri mostravano un'immagine rotta. Ospitarli in locale elimina anche 16 richieste esterne a ogni caricamento.

I marchi restano dei rispettivi titolari: AWS e Azure sono stati tolti da simple-icons su richiesta di Amazon e Microsoft. Se MetisT aderisce ai loro programmi partner, sostituite quei due file con i loghi ufficiali forniti dai programmi.

## Font

`fonts/` contiene DM Sans e DM Serif Display in WOFF2, solo i sottoinsiemi latin e latin-ext. Sono ospitati sul sito invece che caricati da Google Fonts: in questo modo l'indirizzo IP dei visitatori non viene trasmesso a Google. Le regole `@font-face` sono incorporate in `index.html`.

Licenza SIL Open Font License: i testi sono in `OFL-dmsans.txt` e `OFL-dmserifdisplay.txt` e vanno tenuti insieme ai file dei font.

## Foto

`img/` contiene le 33 foto del sito, provenienti da Unsplash. Sono ospitate sul sito invece che caricate da images.unsplash.com: nessun IP dei visitatori viene trasmesso a Unsplash e nessuna foto può sparire perché rimossa dall'origine. Il nome del file riporta l'identificativo della foto su Unsplash e la larghezza.

La licenza Unsplash consente l'uso gratuito, anche commerciale, senza obbligo di attribuzione.

