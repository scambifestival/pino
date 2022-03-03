<cite>Pino</cite> is a concept for a webapp aimed at handling (hence both reading and writing) <cite>[Scambi Festival][scambi]</cite>’s database where guests, participants, laboratories, sponsors, ideas, etc. are collected.

<br>
<br>

## Databases

<cite>Pino</cite> is not a single database, but rather the aggregation of several sub-databases.  
Such databases are:

- [**Relations**](Relations.md)**, a record of all of the organizations and individuals that joined across the editions of Scambi Festival.
- [**<i lang='it'>Libro Soci</i>**](Libro Soci.md), the Italian name for the “members book”, a record of all of current and previous associates of our non-profit that we are compelled by law to record.
- [**Staff**](Staff.md), an extended version of <i lang='it'>Libro Soci</i>, including not only those that are officially and legally affiliated to us, but also those who temporarily joined as volunteers, helped us during special occasions, or <i lang='it'>soci</i> (members) who did not renew their subscription.
- [**<cite lang='it'>Dissolvenze</cite>**](Dissolvenze.md), a record of all the people who joined <cite lang='it'>[Dissolvenze: i corti di Scambi](https://scambi.org/dissolvenze)</cite>, our short movie contest
- [**Public**](Public.md), the record of all the people who participated to Scambi Festival across different editions
- [**Newsletter**](Newsletter.md), data of all the people who subscribed to our newsletter

#### Notes

- Sub-lists are arrays
- databases should “talk” to each other, and, ideally, some automations should be established in order to to automatically populate them. Details about such automations are explained in “Connections” and “Automations” sections in every single one of the files above.
- When it is mentioned that something is entered “manually” into the database, it does not mean that it should be entered through direct access to the database, but rather by using the GUI limited to Scambi staff only

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

- [ ] expanding the use of Pino to ideas and proposals collection, of any sort.

<br>
<br>

## To figure out

- What is the most stable and/or reliable way to add/edit/remove entries to those databases, while keeping it as simple as possible (any non-techie should be able to do so)
- How to handle simultaneous editing of fields? (This should not happen often, yet it could cause inconsistencies or version conflicts)

<br>
<br>




[scambi]: https://scambi.org 'Scambi Festival official website'
