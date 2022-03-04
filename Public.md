## Description

*Public* collects all of the information concerning people who joined Scambi Festival as audience.

<br>
<br>

## Automations

- This database should be strictly connected to the booking platform. Maybe, it could even be its backend.
- people who provide an `username` should be automatically subscribed to [Scambi Festival’s Telegram channel](http://t.me/scambifestival 'Link to “Scambi Festival” channel, on Telegram')

<br>
<br>

## Fields

- `first name`: `Max`
- `second name`: `Weber`
- `birth date`: `1864-04-21` (this way, it is possible to deduce the age and have some understanding of the average age of people participating)
- `email`: `max@weber.me`
- `username`: the Telegram username of this person
- `activities`: an array listing all of the activities this person took part to, by linking to entries of [Program]. This field is crucial, since it is the one that is manipulated the most through the booking platform. Since every activity occurrence [should have a token](Program.md#token), it is possible to know precisely how many people and who participated to each occurrence; in this way, the booking platform can show related data.
- `editions`: this could be automatically deduced by analyzing `activities`; nevertheless, it is an array of the years of the editions this person participated to (e.g. `[2021,2022]`).

#### Note

Only **`bold fields`** are required.

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
[lab]: https://scambi.org/laboratori
[pinoli]: https://scambi.org/pinoli
