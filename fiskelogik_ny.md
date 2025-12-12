# Fiskelogik - Ny Logikgåta (SLUTGILTIG VERSION)

## Pusseltext

**Nivå 4: Fiskelogik**

Fyra fiskare fångar fyra olika fisketyper med fyra olika metoder. Matcha rätt fiskare med rätt fisk och metod baserat på ledtrådarna:

**Ledtrådar:**

1. Erik fiskar inte abborre eller gädda.
2. Lisa använder inte flugfiske eller grundfiske.
3. Olle fiskar inte lax eller ruda.
4. Sara använder inte spinnfiske eller flugfiske.
5. Den som fiskar lax använder inte grundfiske.
6. Den som fiskar abborre använder inte isfiske.
7. Den som fiskar gädda använder inte flugfiske.
8. Den som fiskar ruda använder inte spinnfiske.
9. Den som använder flugfiske fiskar inte abborre eller gädda.
10. Den som använder spinnfiske fiskar inte lax eller ruda.
11. Den som använder grundfiske fiskar inte lax eller abborre.
12. Den som använder isfiske fiskar inte gädda eller abborre.
13. Exakt en av (Erik, Olle) fiskar lax eller ruda.
14. Exakt en av (Lisa, Sara) använder grundfiske eller isfiske.
15. Erik använder antingen flugfiske eller spinnfiske.
16. Olle använder antingen grundfiske eller isfiske.

---

## Facit (DÖLJ I PUSSELTEXTEN)

| Person | Fisk | Metod |
|--------|------|-------|
| Erik | Lax | Flugfiske |
| Lisa | Abborre | Spinnfiske |
| Olle | Gädda | Grundfiske |
| Sara | Ruda | Isfiske |

---

## Uniqueness Check

**Kontroll av entydighet:**

Från ledtråd 1 och 3: Erik fiskar lax/ruda, Olle fiskar abborre/gädda. Ledtråd 13 säger att exakt en av dem fiskar lax/ruda, så Erik fiskar lax eller ruda, och Olle fiskar abborre eller gädda.

Från ledtråd 3: Olle fiskar abborre eller gädda. Från ledtråd 16: Olle använder grundfiske eller isfiske. Från ledtråd 11: Grundfiske fiskar inte lax eller abborre, så grundfiske fiskar gädda eller ruda. Från ledtråd 3: Olle fiskar inte ruda, så om Olle använder grundfiske fiskar han gädda.

Från ledtråd 12: Isfiske fiskar inte gädda eller abborre, så isfiske fiskar lax eller ruda. Från ledtråd 3: Olle fiskar inte lax eller ruda, så Olle kan inte använda isfiske. Därför använder Olle grundfiske och fiskar gädda.

Nu har vi: Olle = Gädda + Grundfiske.

Från ledtråd 13: Exakt en av (Erik, Olle) fiskar lax/ruda. Olle fiskar gädda, så Erik fiskar lax eller ruda. Från ledtråd 15: Erik använder flugfiske eller spinnfiske. Från ledtråd 10: Spinnfiske fiskar inte lax/ruda, så Erik måste använda flugfiske. Från ledtråd 9: Flugfiske fiskar lax eller ruda. Från ledtråd 5: Lax använder inte grundfiske (men flugfiske är ok). Så Erik fiskar lax med flugfiske.

Nu har vi: Erik = Lax + Flugfiske, Olle = Gädda + Grundfiske.

Kvar: Lisa och Sara, Abborre och Ruda, Spinnfiske och Isfiske.

Från ledtråd 2: Lisa använder spinnfiske eller isfiske. Från ledtråd 4: Sara använder grundfiske eller isfiske. Från ledtråd 14: Exakt en av (Lisa, Sara) använder grundfiske eller isfiske. Olle använder redan grundfiske, så ingen av dem kan använda grundfiske. Därför använder exakt en av (Lisa, Sara) isfiske.

Från ledtråd 10: Spinnfiske fiskar abborre eller gädda. Gädda är redan taget, så spinnfiske fiskar abborre. Från ledtråd 2: Lisa använder spinnfiske eller isfiske. Om Lisa använder spinnfiske, fiskar hon abborre. Om Lisa använder isfiske, fiskar hon (från ledtråd 12) lax eller ruda. Men lax är redan taget, så hon fiskar ruda. Men ledtråd 6 säger att abborre använder inte isfiske (men det säger inget om ruda). Så Lisa kan använda isfiske och fiskar ruda, eller använda spinnfiske och fiskar abborre.

Från ledtråd 8: Ruda använder inte spinnfiske. Så om Lisa fiskar ruda, kan hon inte använda spinnfiske, så hon använder isfiske. Men från ledtråd 12: Isfiske fiskar inte gädda eller abborre, så isfiske fiskar lax eller ruda. Lax är redan taget, så isfiske fiskar ruda. Så om Lisa använder isfiske, fiskar hon ruda.

Men vänta, om Lisa använder spinnfiske, fiskar hon abborre (från ledtråd 10). Om Lisa använder isfiske, fiskar hon ruda (från ovan). Från ledtråd 6: Abborre använder inte isfiske, så om Lisa fiskar abborre använder hon spinnfiske. Från ledtråd 8: Ruda använder inte spinnfiske, så om Lisa fiskar ruda använder hon isfiske.

Så Lisa kan antingen fiska abborre med spinnfiske, eller ruda med isfiske.

Från ledtråd 14: Exakt en av (Lisa, Sara) använder grundfiske eller isfiske. Olle använder redan grundfiske, så ingen kan använda grundfiske. Därför använder exakt en av (Lisa, Sara) isfiske.

Om Lisa använder isfiske, fiskar hon ruda. Om Lisa använder spinnfiske, fiskar hon abborre.

Om Sara använder isfiske (från ledtråd 4: Sara använder grundfiske eller isfiske), fiskar hon (från ledtråd 12) lax eller ruda. Lax är redan taget, så Sara fiskar ruda. Men om Lisa också använder isfiske och fiskar ruda, så har vi två som fiskar ruda - motsägelse!

Så exakt en av (Lisa, Sara) använder isfiske. Om Lisa använder isfiske, fiskar hon ruda, och Sara använder grundfiske (men det är redan taget) - motsägelse!

Låt mig tänka om. Från ledtråd 4: Sara använder grundfiske eller isfiske. Men Olle använder redan grundfiske, så Sara måste använda isfiske. Från ledtråd 14: Exakt en av (Lisa, Sara) använder grundfiske eller isfiske. Om Sara använder isfiske, så kan inte Lisa använda isfiske. Därför använder Lisa spinnfiske och fiskar abborre.

Nu har vi: Lisa = Abborre + Spinnfiske.

Kvar: Sara, Ruda, Isfiske.

Från ledtråd 4: Sara använder grundfiske eller isfiske. Grundfiske är redan taget, så Sara använder isfiske. Från ledtråd 12: Isfiske fiskar lax eller ruda. Lax är redan taget, så Sara fiskar ruda.

Nu har vi: Sara = Ruda + Isfiske.

Alla är nu tilldelade: Erik = Lax + Flugfiske, Lisa = Abborre + Spinnfiske, Olle = Gädda + Grundfiske, Sara = Ruda + Isfiske.

**Lösningen är entydig!**
