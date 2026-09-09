# Via Guerrieri 7 — pagina trasferita

> **Questa pagina non e' piu' il contenuto vivo.**
> La scheda dell'immobile e' stata assorbita nel sito principale:
> https://www.palieriinvestment.com/immobili/via-guerrieri-7
>
> `index.html` ora e' solo un redirect (canonical + meta refresh + JS: GitHub Pages
> non permette un 301 vero). I testi originali sono nella storia git, al commit 56b76e8,
> e sono stati riversati in `src/lib/guerrieri-content.ts` del repo del sito.
> Aggiornare prezzi o capitolato **qui non ha piu' effetto**: si aggiorna sul sito.

---

Pagina singola per la vendita del trilocale con terrazzo di Via Matteo Luigi Guerrieri 7,
Immacolata, Foggia. Palieri Investment S.r.l.

## Contenuto
- `index.html` — la pagina (HTML, CSS e JavaScript in un unico file)
- `img/` — fotografie e planimetria
- `og.jpg` — anteprima mostrata quando il link viene condiviso su WhatsApp o sui social
- `favicon.png` — icona della scheda del browser

## Pubblicazione
Settings → Pages → Source: **Deploy from a branch** → Branch: **main** / **/(root)** → Save.

Indirizzo pubblico: https://palierinvestment-srl.github.io/via-guerrieri-7/

## Dominio personalizzato
Per servirla su `guerrieri7.palieriinvestment.com`:
1. Settings → Pages → Custom domain → `guerrieri7.palieriinvestment.com`
2. Su Hostinger, record **CNAME**: nome `guerrieri7` → punta a `palierinvestment-srl.github.io`
3. Attendere la verifica, poi spuntare *Enforce HTTPS*

Dopo il cambio di dominio vanno aggiornati `og:url`, `og:image` e `link rel="canonical"`
nell'`index.html`, altrimenti l'anteprima social continua a puntare all'indirizzo vecchio.

## Avvertenza
I contenuti (superfici, capitolato, prezzi, tempistiche) sono provvisori e da confermare
in fase di trattativa. La pagina non costituisce proposta contrattuale.
