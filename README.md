# Gärten Bern

Wer in Bern keinen Balkon hat und gärtnern will, muss wissen, wo die Areale sind und wen man fragt. Die Flächen sind in OpenStreetMap, die Karte dazu fehlte.

Live: **https://richardcervenka111-create.github.io/gaerten-bern/**

Zwei Sprachen (DE/EN), „nächster Punkt“ mit Fussroute, kein Tracking, Standort bleibt im Gerät.

## Daten

Familiengarten-Areale (landuse=allotments) und Gemeinschaftsgärten (garden:type=community) der Stadt Bern aus OpenStreetMap, als Mittelpunkte der Flächen. Für eine Parzelle: Verein des Areals fragen (Name/Website im Punkt, wenn erfasst); der Dachverband ist der Verband der Familiengärtner Bern.

`data.js`: 70 Punkte, OpenStreetMap-Stand 2026-09-24T23:21:05Z, gebaut am 2026-09-25 mit `_tools/make_map_app.py` (Overpass API, Bounding Box Stadt Bern 46.90–46.99 / 7.37–7.50). Lizenz ODbL, © OpenStreetMap-Beitragende. Karte: OSM-Kacheln, Leaflet 1.9.4 (cdnjs, mit Integritätsprüfung).

## Ehrlich gesagt

OpenStreetMap ist so gut wie die Leute, die es pflegen. Fehlt ein Punkt oder stimmt ein Detail nicht: in OpenStreetMap korrigieren, davon haben alle etwas. Diese Seite ersetzt keine offizielle Auskunft der Stadt.

## Lokal

`index.html` im Browser öffnen. Kein Build.

## Lizenz

Code MIT. Daten ODbL (OpenStreetMap).
