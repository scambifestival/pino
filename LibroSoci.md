## Connections

- **Staff**, since it is a superset of this database

<br>
<br>

## Automations

- when the `role` of a member becomes `ex socio`, it should be automatically moved to *Staff*

<br>
<br>

## Fields

- `first name`: `Max`
- `second name`: `Weber`
- `CF`: `MAXWBR00L09E290V` (ID code)
- `birth date`: `1864-04-21`
- `birth place`: `Erfurt, SX, Prussia`
- `email`: `max@weber.me`
- `role`: either `socio` (current member), `ex socio` (previously a member), `socio simpatizzante` (non-active member), `Consigliere` (board member), `Segretario` (Secretary), `Tesoriere` (Treasurer), `Vicepresidente` (Vice President), or `Presidente` (President)
- `PIX`: should be a link to another person in Libro Soci; PIX stands for <q>Partner in Crime Scambi</q> and PIXs are couples of people (*<a href='https://wiki.scambi.org/books/base-knowledge/page/pix' target='_blank' title='PIX - Manuale di Scambiologia' hreflang='it'>What a PIX is</a>* (in Italian, from Scambi’s Wiki))
- `quota associativa`: array of years for which the member has renewed her subscription (e.g. `[2021,2022]`)
- `iscrizione`: the subscription date of this member (e.g. `2020-10-21`)
- `address`: Residence address, e.g. `Via Dante Alighieri 81, 18038 Sanremo (IM), Italy`
- `team`: the team this member is part of (one of <a href='https://wiki.scambi.org/books/base-knowledge/page/gruppi' target='_blank' title='Gruppi - Manuale di Scambiologia' hreflang='it'>these</a>) (e.g. `Libellule`)
