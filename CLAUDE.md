# CLAUDE.md

## Töövool

- **Väldi ilmselgeid küsimusi.** Pigem tee ja küsi hiljem — kasutaja parandab/suunab tulemuse põhjal.
- **Autonoomne feedback-loop.** Tee samm, vaata tulemust, paranda. Ära peatu igal otsusekohal kinnitust küsima.
- Kasutaja võib igal ajal CLAUDE.md ja skille muuta — võta neid muutusi alati arvesse.

## Projekt

Lihtne staatiline ühe-faili veebileht (`index.html`), serveeritud GitHub Pagesilt. Hash-põhine client-side router (vanilla JS). RegMo widget registreerimiseks.

### Lehed
- **Esileht** — hero + alade kaardid (SVG ikoonidega) + CTA
- **Ajakava** — RegMo ajakava (registreerimine sealt)
- **Hinnad** — hinnad + makseinfo

Footer on igal lehel ja sisaldab kontaktinfot (asukoht, telefon, e-post, sotsiaalmeedia).

### Stiil
- Hele teema (valge taust, tume tekst), punane aktsent (#e63946)
- Fondid: Oswald (pealkirjad), Open Sans (sisu)
- Ära kasuta roosaid taustagradiente

### Eelistused
- Üks `index.html` fail, ei ole build-protsessi
- Vanilla JS / CSS, ei lisa raamistikke ilma vajaduseta
