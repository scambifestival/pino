## Description

The purpose of *Relations* is to be a comprehensive archive of all the organizations and individuals Scambi Festival collaborates and collaborated with ins the past.

<br>
<br>

## Connections

Other DBs *Relations* should interact with, how, and why:

- **Staff**, as `ref` should point to an entry of this db

<br>
<br>

## Automations

All of these entries are entered manually.

<br>
<br>

## Fields

Comprehensive explanation of the fields of this database:

- **`name`** (in case of `person`)
  - `name`
  - `surname`
- **`organization`**: either the organization the individual belongs to, or the name of the organization itself, in case there is no specific individual
- **`email`**
- **`kind`**: either `organization`, or `person`
- `nationality` (using [ISO 3166-1 alpha-2 country codes](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2 'ISO 3166-1 alpha-2 on Wikipedia'))
- `ref`: link to an entry of [Staff](Staff.md), hence pointing to the staff member who is the responsible of the relations with this org/person
- **`edition`**: an array of all the years of the edition this entity joined:
	- `year`: example number of a year (e.g. `2021`)
		- **`role`**, an array listing all of the roles this entity joined the festival as, during the edition of year (e.g. all of the roles that entity had during `2021` edition):
			- `public`: this person participated as audience
			- `pinolo`: this entity held a [Pinolo](https://scambi.org/pinoli '“Pinoli„ on scambi.org')
			- `lab`: this entity held a [Laboratory](https://scambi.org/laboratorio '“Laboratorio„ on scambi.org')
			- `sponsor`: this entity gave us money
- `notes`: possible annotations
