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
