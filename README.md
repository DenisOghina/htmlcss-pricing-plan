# htmlcss-pricing-plan

Esercizio da fare da soli dopo la lezione di martedì 3/11 (container e colonne con Flexbox).

## Consegna

Riproduci la pagina con i piani prezzo degli screenshot. Deve adattarsi alla larghezza della finestra: su mobile i piani stanno uno sotto l'altro, man mano che lo spazio cresce si affiancano, fino a tre colonne su desktop.

Si fa con quello che abbiamo visto a lezione: container, `flex-wrap`, `gap` e `calc()`. **Niente media query**: le vediamo giovedì.

Lavora con l'inspector aperto e trascina il bordo della finestra per vedere come si comporta la pagina da stretta a larga.

## Cosa trovi qui

```
├── index_scheletro.html          ← la struttura HTML della pagina, senza stile (facoltativa)
├── screenshot-mobile.png         ← la pagina su un telefono
├── screenshot-desktop.png        ← la pagina su uno schermo largo
└── screenshot-tablet-bonus.png   ← come appare in mezzo, con i bonus
```

- Font: un generico **sans-serif**
- Icone: **Bootstrap Icons** (spunta, croce, interruttore)

## Come procedere

1. Fai il **fork** di questa repo: bottone **Fork** in alto a destra, lascia il nome `htmlcss-pricing-plan`. Il fork è la tua consegna: così il docente la vede.
2. Clona il **tuo** fork sul computer (`git clone` con l'indirizzo del tuo fork, non di questa repo).
3. Crea nella cartella `index.html` e `style.css` e lavora lì. Se vuoi partire dalla struttura già pronta, copia `index_scheletro.html` in `index.html`: ti resta da scrivere tutto il CSS. Le classi sono un suggerimento, puoi cambiarle.
4. Fai commit e push sul tuo fork.

Obiettivi passo passo, come verificarli e suggerimenti sono nella pagina **Container e colonne** che trovi nel canale del corso, sezione *Esercizio: Pricing Plan*. Per ripassare: [dispensa Layout](https://kb-aiwd.andreadev237.workers.dev/lezioni/css-layout) e [dispensa Flexbox](https://kb-aiwd.andreadev237.workers.dev/lezioni/css-flexbox).

Se usi l'AI, il file `AGENTS.md` la fa lavorare da tutor: ti fa domande e ti indica dove guardare, senza darti la soluzione.

## Bonus (facoltativi)

Guarda `screenshot-tablet-bonus.png`.

- Quando nella riga entrano solo 2 card, la terza prende tutta la riga.
- Quando una card prende tutta la riga, la lista delle feature si sistema su 2 colonne.

## Consegna

Nessuna scadenza: lo correggiamo insieme giovedì. Fai push sul tuo fork, poi incolla il link nel canale del corso e scrivi se hai fatto dei bonus.
