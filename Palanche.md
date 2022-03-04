## Description

*Palanche* are the **books** of [A.P.S. Oltre](https://scambi.org/oltre), the association that is the legal organizer of Scambi Festival, in this database are stored all of the transactions made to and by our association. The purpose of this database is to <u>make bookkeeping activities as simple as possible</u>. 

<br>
<br>

## Automations

- Each and every one of the entries having a `budget` field should be automatically added to *Palanche*, with `planned` as `date`.

<br>
<br>

## Fields

- `date`: when this transaction occurred, in [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601 'ISO 8601 on Wikipedia') format. In case this is a planned budget expense or income, this field should have `planned` as its value.
- `what`: short description of what the transaction is
- `amount`: number of € involved in the transaction. Of course, a negative number is an expense, while a positive one is an income.
- `via`: the method used for the transaction, that can be either:
  - `cash`
  - `bonifico` (wire transfer)
  - `PayPal`
- `receipt`: the receipt for this transaction. Decide between one of the two possible implementation possibilities: filling this field with an URL linking to the shared file of the receipt [on our cloud](https://nuvola.scambi.org), or directly attaching the receipt to the database.
- `notes`: any additional information

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
