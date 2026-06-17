# Esercizio 1 — Home page · Flexbox base

**Sito:** *Da Gennaro*, pizzeria napoletana a Torino.
**Pagina da realizzare:** `index.html` (la home).

## Obiettivo
Costruire la home da zero — HTML e CSS, reset compreso — usando Flexbox per
tutti gli allineamenti. Niente `position` per il layout.

## Cosa deve contenere la pagina (dall'alto in basso)
1. **Header** navbar con logo a sinistra, menù di navigazione al centro/destra, bottone "Prenota" a destra.
2. **Hero** a tutta larghezza: titolo, sottotitolo, due bottoni. Testo e bottoni centrati, immagine di sfondo scura con overlay.
3. **"Perché noi"**: tre colonne uguali, ognuna con icona, titolo, testo.
4. **Info**: due blocchi affiancati — *Orari* e *Dove siamo*.
5. **Recensioni**: tre citazioni in colonna.
6. **Footer** semplice: nome a sinistra, link a destra.

## Requisiti tecnici Flexbox
- Nell'header ci deve essere un contenitore flex che contiene il logo (testuale) che deve essere un link alla home, un nav con i link di navigazione e un bottone 'prenota'.
- Anche la lista dei link `<ul>` è un flex con `gap`.
- L'hero ha un'altezza minima, un'immagine di background e centra il contenuto sui due assi.
- I due bottoni dell'hero sono allineati con flex.
- Le tre colonne ("perché noi" e recensioni) sono flex con i figli che occupano la stessa quantità di spazio.
- Nelle righe degli orari, etichetta a sinistra e valore a destra grazie a flex.

## Requisiti trasversali
- Tutto il sito usa **un solo file `style.css`**: qui impostate reset, variabili, header, footer.
- **Reset CSS** in cima al foglio di stile.
- **Custom properties** (variabili CSS) almeno per i colori (palette scelta da voi) e i font.
- **1–2 font da Google Fonts** (uno per i titoli, uno per il testo).
- **Icone Lucide Icons** da copiare e incollare l'svg dell'icona scelta dove vi serve.
- **Responsive desktop-first**: breakpoint a `768px` e `480px` con `max-width`.

## Immagini
Una sola immagine, di sfondo all'hero. Prendetela da **Unsplash** o **Freepik**.
Mettete un overlay scuro per rendere leggibile il testo bianco.

## Testo da usare
- **Logo:** Da Gennaro
- **Menù:** Home · Menù · Chi siamo · Contatti
- **Titolo hero:** La vera pizza napoletana, nel cuore di Torino
- **Sottotitolo:** Impasto a lunga lievitazione, forno a legna e ingredienti scelti. Dal 1987, in Borgo San Salvario.
- **Bottoni hero:** Vedi il menù · Prenota un tavolo
- **Perché noi:**
  - `icona fuoco` Forno a legna — Cottura a 450°C in 90 secondi. Cornicione alto, leggero e ben cotto.
  - `icona orologio` Impasto a 48 ore — Lievitazione lenta a temperatura controllata, per una pizza più digeribile.
  - `icona foglia` Ingredienti scelti — Pomodoro San Marzano DOP, fiordilatte di giornata, basilico fresco.
- **Orari:** Lun–Gio 19:00–23:30 · Ven–Sab 12:30–14:30 e 19:00–00:00 · Domenica 12:30–15:00 e 19:00–23:30
- **Dove siamo:** Via Belfiore 12, 10125 Torino — Borgo San Salvario · 011 000 0000 · ciao@dagennaro.it
- **Recensioni:**
  - «La margherita più buona che abbia mangiato fuori da Napoli. Cornicione perfetto.» — Sara M.
  - «Locale piccolo e accogliente, servizio gentile e prezzi onesti. Ci torniamo ogni mese.» — Davide R.
  - «Impasto leggerissimo, si sente la lievitazione lunga. Provate la bufala.» — Giulia T.
- **Footer:** Da Gennaro — Pizzeria Napoletana

> I link a `menu.html` e `chi-siamo.html` non funzioneranno ancora.

## Vincoli
- Solo Flexbox per il layout. Niente `float`, niente `position: absolute` per disporre i blocchi.

## Checklist di consegna
- [ ] Reset + custom properties + font Google in cima
- [ ] Header allineato come da consegna
- [ ] Hero centrato sui due assi
- [ ] Tre colonne uguali
- [ ] Sotto 768px tutto si incolonna correttamente
- [ ] Nessuno scroll orizzontale su mobile

## Bonus (facoltativo)
- Effetto `:hover` sui bottoni e sui link.
