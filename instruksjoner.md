# Instruksjoner

## Instruksjonsformat

Alle instruksjoner er 4 tribbles. Følgende formater for hva de kan bety er tillatt:

| Opkode | Mål | Kjelde 1 | Kjelde 2 |
| Opkode | Mål | Spontan verdi |
| Opkode | Opkodeutviding | Spesialinstruksjonsargument |

## Liste over instruksjoner

Vanlege instruksjonar:

| Opkode | Namn               | Mål | Kjelde 1 | Kjelde 2   | Spontan verdi |
| ------ | ------------------ | --- | -------- | ---------- | ------------- |
| 0      | Les                | Til | Addresse | -          | -             |
| 1      | Skriv              | Frå | Addresse | -          | -             |
| 2      | Flytt              | Til | Frå      | -          | -             |
| 3      | Sett               | Til | -        | -          | Verdi         |
| 4      | Pluss              | Til | Ledd 1   | Ledd 2     | -             |
| 5      | Minus              | Til | Ledd 1   | Ledd 2     | -             |
| 6      | Grein              | -   | Addresse | Betingelse | -             |
| 7      | Spesialinstruksjon | -   | -        | -          | -             |

Spesialinstruksjonar:

| Opkodeutviding | Namn       | Argument |
| -------------- | ---------- | -------- |
| 0              | Vis        | Kjelde   |
| 1              | Brukartal  | Mål      |
| 2              | Fyrverkeri | -        |
| 3              | Tilfeldig  | Mål      |
| 4              |            | -        |
| 5              |            | -        |
| 6              |            | -        |
| 7              |            | -        |

### Grein

Grein-instruksjonen sett programtellaren til addressa frå kjelde 1 dersom betingelsesverdien frå kjelde 2 er større enn eller lik 0
