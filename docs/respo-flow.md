# SDSA im RESPO-Flow

RESPO ist der Anker des Systems und lädt SDSA als Achsenbasis.

SDSA liefert:
- 81 Achsen
- 360° Stabilisationsvektor
- TMP-Daten aus /src/hdf
- Achsen für PQ und PP
- Achsen für XTOM und MEAT

RESPO interpretiert SDSA und erzeugt daraus:
- Achsenfluss
- Routing
- Stabilisationspunkte
- Übergänge zu PQ und PP

RESPO → SDSA → PQ/PP → XTOM → MEAT
