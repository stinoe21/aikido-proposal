# Back to Being × Aikido: partnership pitch

Een partnervoorstel voor **Aikido Security** (all-in-one AppSec-platform, Gent). Statische HTML/CSS/JS, geen build, geen dependencies. Zelfde visuele taal als de Figma-, Analogue- en n8n-decks.

## De kern

Wij bouwen de MIND-app handsfree op de Camino: de AI-agents schrijven de code, wij sturen met stem en joystick. AI-gegenereerde ("vibe-coded") code gaat snel, en snel gaan fouten mee: gelekte keys, kwetsbare dependencies, checks die niemand schreef. Het is een mentale-gezondheidsapp met de gevoeligste data die er is. **Aikido scant alles wat de agents schrijven, vóór het MIND bereikt** - het bewijs dat door AI gebouwde software veilig genoeg is om over te dragen. De vraag: Aikido als productpartner (platformtoegang) + een sponsoring van de reis. Aikido krijgt een live proof-case ("we secured an app built entirely by AI, on a mountain") plus zichtbaarheid, optioneel een mini-docu.

De brug is hun eigen regel, uit Aikido's vibe-coding checklist: *"If it's worth building, it's worth securing."* (staat als kicker op slide 5).

## Slide-structuur (9 slides)

1. Cover (back to being × Aikido)
2. Thesis: being busy isn't being present
3. What we do: the world as our office (The Walk + AI-agents + route)
4. Where Aikido comes in: AI writes the code, it still has to be safe (3 kolommen)
5. Why MIND: MIND is the whole point (+ Aikido-kicker "if it's worth building...")
6. The app for MIND: a weather report for your mind (+ where Aikido fits)
7. The ask: twee vormen van steun + wie er al in zit
8. The proposal: twee tiers (The foundation / The film - onze voorkeur)
9. Close: from first commit to safe handover

## Aanpassen

- **Copy:** in de `<section class="slide ...">` blokken in `index.html`.
- **De ask (slide 7 + 8):** nu "Aikido product access" + "sponsorship of the journey", tiers als scope-niveaus. Vul concreet in zodra de mail/het gesprek de exacte vraag scherp heeft (bv. welke Aikido-tier, welk sponsorbedrag).
- **Sponsorlijst (slide 7):** nu `Wispr Flow, Remote, Helloprint, Watermelon en n8n`. Voeg toe/haal weg naar gelang wie bevestigd is (website noemt ook Techleap, AI.AM, LerAI, TAG).
- **Accentkleur (Aikido):** `--aikido: #6551F3` (violet/indigo), `--aikido-cyan: #17DFDC`, uit Aikido's live merk-CSS. Bovenin het `<style>`-blok.
- **Aikido-logo:** nu als woordmerk ("Aikido") in de merkkleur gezet (cover + brandlock). Vervang door hun eigen SVG-logo uit de [press kit](https://www.aikido.dev/company/press-kit) als je dat inlaadt.
- **Contact:** `stijnysmit@gmail.com` (slide 9).

## Openen

Dubbelklik `index.html`, of `python -m http.server 4173` en open `http://localhost:4173`. Pijltjes / spatie / swipe om te navigeren.

## PDF exporteren

Al gegenereerd als `Back-to-Being-x-Aikido.pdf` (9 pagina's, 1280x720 per slide, achtergronden aan). Opnieuw genereren via Chrome: `Ctrl+P` -> Opslaan als PDF -> Liggend -> Marges: Geen -> Achtergronden: Aan. De print-styling zet elke slide op een eigen 1280x720-pagina zonder navigatiebalk.
