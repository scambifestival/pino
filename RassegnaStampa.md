## Description

In Italian, <em lang='it'>rassegna stampa</em> stands for the collection of all press mentions concerning a specific topic. In Scambi, the <i lang='it'>Chiocciole</i> team is in charge of keeping it updated, for all of our press releases that get published as well as for all articles that mention us.

<br>
<br>

## Automations

Grouping publications by `what`:

- parsing a list of articles for each event, in `https://scambi.org/press` (English version), and in `https://scambi.org/stampa` (Italian version)
- using some document generator to generate a PDF listing all articles for each event, to be downloaded from the two pages above.

<br>
<br>

## Fields

- `date`: article publication date
- `what`: what specific activity, event, or edition is the article about? (e.g. <cite>Scambi Festival 2021</cite>
- `title`: title of the article
- `masthead`: where the article was published
- `author`: the author of the article
- `url`: link to the article
- `lang`: language of the publication
- `notes`: eventual comments or notes