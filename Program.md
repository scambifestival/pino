## Description

*Program* is the aggregation of all the programs of every edition of Scambi Festival. [Workshops][lab], book presentations, *[pinoli]*, flash mobs, you name it: **everything** that happens during the festival should be present there.

#### Note

Of course, *Program* refers to an edition at a time. Nevertheless, it is crucial that in the future we will be able to simultaneously browse through all of the activities we did during many years; hence, it should be decided whether all of the entries of *Program* should populate one database only, having an `edition` field, specifying when the entry happened (like in [Relations]), or if it is better to create a *Program* database for each year, e.g. `Program2021`, `Program2022`, and so on.

<br>
<br>

## Automations

- Once the new <https://scambi.org> is born, the optimal way to make it work is to automate the creation of a page for every single entry of the program database, so that every time something is added and/or changed in *Program*, the public information changes, too. Nevertheless, staff members should be able to <u>decide what is publicly displayed</u> (published on the website) and what is not.
- The `budget` field should be automatically synchronized with a corresponding entry in [Palanche].

<br>
<br>

## Fields

- `title`: title of the event, e.g. `Aromatizing Beer`
- `description`: public description of the activity, **using Markdown syntax**, so that on the website it is rendered beautifully
- `ref`: as in [Relations], link to the member of the [Staff] that is following the organization of this activity, a.k.a. the reference person.
- `host`: link to [Relations], listing one or more organizations or people involved in this activity
- `location`: where in the neighborhood it is taking place, e.g. [`Piazza Dei Dolori`](https://www.openstreetmap.org/way/327173881 '“Piazza dei Dolori„ on OpenStreetMap'). This field is a link to an entry in [Locations].
- `duration`: number of minutes this activity lasts for, e.g. `90`
- `times`: array of times and dates this activity takes place at, e.g. `['2022-08-25T10:30:00+01:00', '2022-08-25T14:30:00+01:00', '2022-08-26T10:30:00+01:00', '2022-08-26T14:30:00+01:00']` (note that times are stored according to the [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601 'ISO 8601 on Wikipedia') format. Every occurrence of any activity should have <strong id=token>an automatically generated token</strong>, so that [Public] can refer not to one activity only, but to the specific occurrence one person participates to.
- `people`: maximum people allowed to this activity
- `material`: an array listing any material that is needed by this activity (e.g. `["pencils", "whiteboard", "a rope"]`)
- `budget`: number in € quantifying the cost of this activity. This field should automatically populate [**<i lang='it'>Palanche</i>**][Palanche].
- `notes`: any sort of additional notes

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
