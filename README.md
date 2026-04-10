# Codice sconto Michael Kors, recupero automatico da shopilo.it

Modulo Python per il recupero automatico di **codici sconto Michael Kors** da [shopilo.it](https://shopilo.it/negozi/michaelkors.it). Restituisce **coupon Michael Kors** attivi in formato JSON, pronto per l'integrazione in un bot Telegram, estensione del browser o qualsiasi altro strumento.

**Pagina live:** [shopilo-it.github.io/codice-sconto-michaelkors](https://shopilo-it.github.io/codice-sconto-michaelkors/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Installazione

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-it/codice-sconto-michaelkors
cd codice-sconto-michaelkors
python fetch.py
```

## Output di esempio

```json
[
  {
    "store": "Michael Kors",
    "code": "SHOPILO15",
    "discount": "15%",
    "description": "15% di sconto su borse e accessori",
    "expires": "2026-10-10",
    "source": "https://shopilo.it/negozi/michaelkors.it"
  }
]
```

## Coupon Michael Kors disponibili

| Sconto | Descrizione | Fonte |
|----------|-----------|-------|
| 15% | 15% di sconto su borse e accessori | [shopilo.it](https://shopilo.it/negozi/michaelkors.it) |

Codici attivi: **[shopilo.it/negozi/michaelkors.it](https://shopilo.it/negozi/michaelkors.it)**

## Domande frequenti

### Come utilizzo un codice sconto Michael Kors?
Copia il codice dalla tabella qui sopra o da [shopilo.it](https://shopilo.it/negozi/michaelkors.it), aggiungi i prodotti al carrello su Michael Kors e inserisci il codice al checkout nel campo dedicato.

### Quanto durano i coupon Michael Kors?
Ogni coupon ha una data di scadenza indicata nella colonna "Scadenza". Lo script fetch.py restituisce solo i coupon attivi al momento dell'esecuzione.

### Dove trovo i voucher Michael Kors piu recenti?
La pagina [shopilo.it/negozi/michaelkors.it](https://shopilo.it/negozi/michaelkors.it) viene aggiornata quotidianamente con i codici sconto Michael Kors, voucher Michael Kors e coupon promozionali Michael Kors piu recenti.

### Il codice non funziona. Cosa faccio?
Verifica la data di scadenza e le condizioni (importo minimo del carrello, prodotti idonei). Alcuni codici sono validi solo nell'app mobile o per il primo ordine.

## Informazioni su Michael Kors

Michael Kors e uno dei negozi online piu popolari. Su [shopilo.it](https://shopilo.it/negozi/michaelkors.it) trovi i migliori codici sconto Michael Kors, coupon Michael Kors verificati e voucher Michael Kors attivi, aggiornati ogni giorno.

## Installazione npm

```bash
npm install codice-sconto-michaelkors
```

```javascript
const { fetchCoupons } = require('codice-sconto-michaelkors');
fetchCoupons().then(data => console.log(data));
```

## Licenza

MIT, dati prelevati da [shopilo.it](https://shopilo.it)
