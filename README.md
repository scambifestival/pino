<cite>Pino</cite> is a concept for a webapp aimed at handling (hence both reading and writing) <cite>[Scambi Festival][scambi]</cite>’s database where guests, participants, laboratories, sponsors, ideas, etc. are collected.

<br>
<br>

## Roadmap

Pino should allow users to:

### MVP

- [ ] Add entries to the database
- [ ] Search for entries
- [ ] Filter search results according to arbitrary [parameters](#fields)
	- [ ] when filtering, the `role` field should not be dependent of the year: I should look for roles regardless of the year, and potentially later decide to get only the roles of a determined edition. 

### Further development

- [ ] expanding the use of Pino to ideas and purposals collection, of any sort.

<br>
<br>

## Fields

Comprehensive explanation of the fields of the database:

- **`name`** (in case of `person`)
  - `name`
  - `surname`
- **`organization`**: either the organization the individual belongs to, or the name of the organization itself, in case there is no specific individual
- **`email`**
- **`kind`**: either `organization`, or `person`
- `nationality` (using [ISO 3166-1 alpha-2 country codes](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2 'ISO 3166-1 alpha-2 on Wikipedia'))
- `ref`: who in the Festival staff is the reference person for this entity
- **`edition`**: an array of all the years of the edition this entity joined:
	- `YEAR_NUMBER`: example number of a year
		- **`role`**, an array listing all of the roles this entity joined the festival as, during the edition of year `YEAR_NUMBER`:
			- `public`: this person participated as audience
			- `pinolo`: this entity held a [Pinolo](https://scambi.org/pinoli '“Pinoli„ on scambi.org')
			- `lab`: this entity held a [Laboratory](https://scambi.org/laboratorio '“Laboratorio„ on scambi.org')
			- `staff`: this person joined as member of the staff
			- `sponsor`: this entity gave us money
			- `dissolvenze`: this person participated to <cite>[Dissolvenze](https://scambi.org/dissolvenze 'Dissolvenze on scambi.org')</cite>
			- `volunteer`: this person joined as volunteer
- `notes`: possible annotations

#### Notes

- Sub-lists are arrays
- bold fields are fundamental, others are extras

[scambi]: https://scambi.org 'Scambi Festival official website'
