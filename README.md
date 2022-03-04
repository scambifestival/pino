<cite>Pino</cite> is a concept for a webapp aimed at handling (hence both reading and writing) <cite>[Scambi Festival][Scambi]</cite>’s database where guests, participants, laboratories, sponsors, ideas, etc. are collected.

<br>
<br>

## Databases

<cite>Pino</cite> is not a single database, but rather the aggregation of several sub-databases.  
Such databases are:

- **[Relations]**, a record of all of the organizations and individuals that joined across the editions of Scambi Festival.
- **[Program]**, a collection of all the [laboratories][lab], [pinoli], and anything that constitutes every edition of Scambi Festival. What [Relations] is with respect to people and guests, [Program] is with respect to content and activities.
- **[Ideas]**, a record of all the ideas for guests and laboratories, containing information about the status of potential proposals submitted to them.
- [**<i lang='it'>Libro Soci</i>**][Libro Soci], the Italian name for the “members book”, a record of all of current and previous associates of our non-profit that we are legally required to keep track of.
- **[Staff]**, an extended version of <i lang='it'>Libro Soci</i>, including not only those that are officially and legally affiliated to us, but also those who temporarily joined as volunteers, helped us during special occasions, or <i lang='it'>soci</i> (members) who did not renew their subscription.
- [**<i lang='it'>Palanche</i>**][Palanche], financial records
- [**<cite lang='it'>Dissolvenze</cite>**][Dissolvenze], a record of all the people who joined <cite lang='it'>[Dissolvenze: i corti di Scambi](https://scambi.org/dissolvenze)</cite>, our short movie contest
- **[Public]**, the record of all the people who participated to Scambi Festival across different editions
- **[Newsletter]**, data of all the people who subscribed to our newsletter
- **[Locations]**, associating coordinates to the names of locations where Scambi Festival activities take place.

#### Notes

- Sub-lists are arrays
- databases should “talk” to each other, and, ideally, some automations should be established in order to to automatically populate them. Details about such automations are explained in “Connections” and “Automations” sections in every single one of the files above.
- When it is mentioned that something is entered “manually” into the database, it does not mean that it should be entered through direct access to the database, but rather by using the GUI limited to Scambi staff only

<br>
<br>

## Features

### Data management

- [ ] Use a library or a software, or alternetively, develop a Telegram bot to easily manipulate any entry of *Pino*
- [ ] Consider how *Pino* should behave in case multiple people are editing the same database (seldom would occur that multiple users are editing the same entry)

<br>

### Data visualization

Data visualization, as of right now, is secondary, since we do not have much data to visualize, yet. We are more focused on [managing](#Data management) it.

- [ ] Add entries to the database
- [ ] Search for entries
- [ ] Filter search results according to arbitrary [parameters](#fields)
	- [ ] when filtering, the `role` field should not be dependent of the year: I should look for roles regardless of the year, and potentially later decide to get only the roles of a determined edition. 

<br>

### Further ideas

Transforming Pino in a (social media like) platform where people and independent festivals’ organizers could share and clone ideas and formats for contents, laboratories, etc.

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
