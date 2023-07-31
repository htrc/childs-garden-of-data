README for workset directory

# Introduction
The `workset` directory contains multiple data files with metadata about the workset and its volumes. Details about each file, its format, and structure are included below
explain:

# `*.csv`

These simple CSV files list the volume ID and some additional metadata for each volume in the workset.

The columns in the CSV files are:

- id (volume identifier)
- title 
- year (year of publication)
- language (volume language represented as ISO-369-3 language code) <!-- is this correct? -->
- authors

Example:

| id | title | year | language | authors |
|:---|:---   |:---  |:---      |:---     |
| mdp.39015019159832 | Song and dance man /	| 1988	| eng	| Ackerman, Karen, 1951-; Gammell, Stephen, |
| uva.x006114314	| Nine days to Christmas, | 1959 | eng | Ets, Marie Hall, 1895-1984; Labastida, Aurora, |
| mdp.39015013404689 | Arrow to the sun : a Pueblo Indian tale / | 1974 | eng | McDermott, Gerald; McDermott, Gerald, |

# `*native-authored-works*.json`

The JSON files include some basic metadata about the workset itself, including the creators of and contributors to the workset. Also included is a list of workset IDs as persistent links to the items in the [HathiTrust Digital Library](https://hathitrust.org).

