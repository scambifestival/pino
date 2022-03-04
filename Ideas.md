## Description

*Ideas* collects all of the possible ideas we have, in any term: guests, sponsors, formats, scenographic elements, etc…

In case an entry corresponds to a person, the purpose of this database becomes to keep track of the status of the dialogue with them, hence whether they accepted to join, refused, did not answer, etc…

<br>
<br>

## Automations

- Automatically adding entries by reading the messages sent on the Telegram group <cite>SCAMBIDEE</cite>, where any member of the staff could write ideas that pop up in their mind. Messages are sorted and ordered arbitrarily by who writes them by using hashtags. To have a clearer idea of what the group looks like, please [DM Tommi](https://t.me/xplosionmind).

<br>
<br>

## Fields

Comprehensive explanation of the fields of this database:

- `ref`: link to an entry of [Staff](Staff.md), hence pointing to the staff member who is the responsible of the relations with this org/person (who sent the message on the Telegram group)
- `tag`: grouping ideas according to their representative kind which might be one or more of the following:
  - `#lab` (idea for a workshop activity), `#format` (ideas for formats),
  - `#visual` (graphical/design idea),
  - `#sponsor` (potential sponsor idea),
  - `#scambio` (possible collaborations and/or partnerships),
  - `#social` (social media marketing ideas),
  - `#music` (music-related ideas),
  - `#merch` (ideas for perks and merchandising)
- `content`: content of the Telegram message / description of the idea
- `status`: in case this idea refers to a person or an organization, this field keeps track of the status, and it is **either**:
 - `to be contacted`
 - `sent`, a message/email has been sent, but no answer has been received, yet
 - `dialoguing`, the email has been answered and a dialogue has started
 - `ok`, when the status becomes “ok”, it means that this is not an idea anymore, but it is something sure to be added to the **Program**, and/or to [Relations](Relations.md)

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
