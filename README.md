# Gamla tentor i Sverige: var de finns på 24 lärosäten

Öppen datamängd över var gamla tentor finns på svenska universitet och högskolor: eget tentaarkiv,
sektionernas arkiv, inloggning, hur långt bakåt och om facit följer med. Varje uppgift har källa och
datum från lärosätets egna sidor.

Senast uppdaterad: 2026-10-21 (varje uppgift har eget kontrolldatum i CSV:n) · Licens: CC BY 4.0 ·
Underhålls av [Tentero](https://tentero.se/gamla-tentor/)

## Kort svar

- Hos statliga lärosäten är gamla tentor allmänna handlingar. Du kan begära ut dem utan att uppge namn
  eller skäl.
- 9 av 24 lärosäten har ett eget tentaarkiv: två öppna och sju bakom inloggning. 9 gör olika per
  institution.
- Där lärosätet anger en tid finns tentor oftast två år bakåt. Fyra lärosäten anger att facit sällan
  följer med.

## Lärosäten

| Lärosäte | Så delas gamla tentor | Direktlänkar och detaljer |
| --- | --- | --- |
| Blekinge tekniska högskola | Bara på begäran | [tentero.se/bth/](https://tentero.se/bth/) |
| Chalmers tekniska högskola | Varierar mellan institutioner | [tentero.se/chalmers/](https://tentero.se/chalmers/) |
| Göteborgs universitet | Varierar mellan institutioner | [tentero.se/gu/](https://tentero.se/gu/) |
| Högskolan i Borås | Bara på begäran | [tentero.se/hb/](https://tentero.se/hb/) |
| Högskolan i Gävle | Öppet på webben | [tentero.se/hig/](https://tentero.se/hig/) |
| Högskolan i Halmstad | Bakom inloggning | [tentero.se/hh/](https://tentero.se/hh/) |
| Högskolan i Skövde | Öppet på webben | [tentero.se/his/](https://tentero.se/his/) |
| Högskolan Kristianstad | Bakom inloggning | [tentero.se/hkr/](https://tentero.se/hkr/) |
| Jönköping University | Bakom inloggning | [tentero.se/ju/](https://tentero.se/ju/) |
| Karlstads universitet | Bakom inloggning | [tentero.se/kau/](https://tentero.se/kau/) |
| Karolinska Institutet | Bara på begäran | [tentero.se/ki/](https://tentero.se/ki/) |
| KTH | Varierar mellan institutioner | [tentero.se/kth/](https://tentero.se/kth/) |
| Linköpings universitet | Varierar mellan institutioner | [tentero.se/liu/](https://tentero.se/liu/) |
| Linnéuniversitetet | Bara på begäran | [tentero.se/lnu/](https://tentero.se/lnu/) |
| Luleå tekniska universitet | Bakom inloggning | [tentero.se/ltu/](https://tentero.se/ltu/) |
| Lunds universitet | Varierar mellan institutioner | [tentero.se/lu/](https://tentero.se/lu/) |
| Malmö universitet | Bara på begäran | [tentero.se/mau/](https://tentero.se/mau/) |
| Mittuniversitetet | Bakom inloggning | [tentero.se/miun/](https://tentero.se/miun/) |
| Mälardalens universitet | Bakom inloggning | [tentero.se/mdu/](https://tentero.se/mdu/) |
| Stockholms universitet | Varierar mellan institutioner | [tentero.se/su/](https://tentero.se/su/) |
| Södertörns högskola | Ej belagt | [tentero.se/sh/](https://tentero.se/sh/) |
| Umeå universitet | Varierar mellan institutioner | [tentero.se/umu/](https://tentero.se/umu/) |
| Uppsala universitet | Varierar mellan institutioner | [tentero.se/uu/](https://tentero.se/uu/) |
| Örebro universitet | Varierar mellan institutioner | [tentero.se/oru/](https://tentero.se/oru/) |

## Så begär du ut en gammal tenta

1. Mejla institutionen som ger kursen eller lärosätets registrator.
2. Ange kurskod, tentamenstillfälle och att du begär tentafrågorna som allmän handling.
3. Be om en digital kopia. Den är ofta gratis.

Färdigt mejl med rätt mottagare: [tentero.se/begar-ut-gamla-tentor/](https://tentero.se/begar-ut-gamla-tentor/)

## Öva på gamla tentor

Metod, tidsplan och vad du gör när tentorna saknar facit:
[tentero.se/ova-pa-gamla-tentor/](https://tentero.se/ova-pa-gamla-tentor/)

## Data

`data/gamla-tentor-larosaten.csv` har en rad per lärosäte (första raden är en kommentar som börjar med
`#`). Varje uppgift ligger i tre kolumner: värdet, källan (`_kalla`) och kontrolldatumet (`_datum`).
Uppgifterna är `state` (statligt lärosäte), `wikidata`, `infoUrl`, `archive`, `yearsBack`, `facit`,
`digital`, `fees` och `requestEmail`. Dessutom finns `slug`, `namn`, `kortnamn`, `verifierad`,
`antal_verifierade_fakta` och `arkivlankar` (namn, adress, ägare, inloggning och kontrolldatum för
varje tentaarkiv, åtskilda med ` | `). Tomt värde betyder okänt, inte nej.

Filen är samma som [tentero.se/data/gamla-tentor-larosaten.csv](https://tentero.se/data/gamla-tentor-larosaten.csv),
hämtad 2026-10-21.

## Rättelser och tillägg

Öppna ett issue med länk till lärosätets eller sektionens egen sida. Vi verifierar och uppdaterar både
datamängden och tentero.se.

## Licens

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Ange ”Tentero (tentero.se)” som källa.
