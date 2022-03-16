## Description

Note that [Staff] is a superset of this database.

<br>
<br>

## Automations

- the `team`, `image` and `bio` fields should automatically populate the entries for each person in the “who we are” page on scambi.org (each sime a new person is added to the db, she should automatically be added to the page of the group she belongs to)
- when the `role` of a member becomes `ex socio`, it should be automatically moved to [Staff]

<br>
<br>

## Fields

- `first name`: `Max`
- `second name`: `Weber`
- `CF`: `MAXWBR00L09E290V` (ID code)
- `birth date`: `1864-04-21`
- `birth place`: `Erfurt, SX, Prussia`
- `email`: `max@weber.me`
- `username`: the Telegram username of this person (e.g. `@maxweber`, that can be exploited to effectively set up/use any Telegram integration
- `role`: either
  - `socio` (current member),
  - `ex socio` (previously a member),
  - `socio simpatizzante` (non-active member),
  - `Consigliere` (board member),
  - `Segretario` (Secretary),
  - `Tesoriere` (Treasurer),
  - `Vicepresidente` (Vice President),
  - `Presidente` (President)
- `PIX`: should be a link to another person in Libro Soci; PIX stands for <q>Partner in Crime Scambi</q> and PIXs are couples of people (*<a href='https://wiki.scambi.org/books/base-knowledge/page/pix' target='_blank' title='PIX - Manuale di Scambiologia' hreflang='it'>What a PIX is</a>* (in Italian, from Scambi’s Wiki)) (e.g. `Tommi`)
- `quota associativa`: array of years for which the member has renewed her subscription (e.g. `[2021,2022]`)
- `iscrizione`: the subscription date of this member (e.g. `2020-10-21`)
- `address`: Residence address, e.g. `Via Dante Alighieri 81, 18038 Sanremo (IM), Italy`
- `team`: the team this member is part of (one of <a href='https://wiki.scambi.org/books/base-knowledge/page/gruppi' target='_blank' title='Gruppi - Manuale di Scambiologia' hreflang='it'>these</a>) (e.g. `Libellule`), to sync with scambi.org
- `image`: URL pointing to the profile image (e.g. `https://upload.wikimedia.org/wikipedia/commons/6/65/Max_Weber%2C_1918.jpg`), to sync with scambi.org
- `bio`: the bio of this person (e.g. `a German sociologist, historian, jurist, and political economist regarded as among the most important theorists of the development of modern Western society.`), to sync with scambi.org
- `documents` either an URL pointing to the filled out PDF on [Nuvola], or an attachment containing the filled out form itself, of the following documents
  - Liberatoria dati (data usage waiver)
  - Liberatoria immagini (images usage waiver)
  - Non-Disclosure Agreement 

[Scambi]: https://scambi.org 'Scambi Festival official website'
[Relations]: Relations.md
[Program]: Program.md
[Ideas]: Ideas.md
[Libro Soci]: LibroSoci.md
[Staff]: Staff.md
[Palanche]: Palanche.md
[Dissolvenze]: Dissolvenze.md
[Public]: Public.md
[Newsletter]: Newsletter.md
[Locations]: Locations.md
[Nuvola]: https://nuvola.scambi.org '“Nuvola„ - Scambi Festival’s cloud'
[lab]: https://scambi.org/laboratori
[pinoli]: https://scambi.org/pinoli
