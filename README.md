# Spotify Top 50 Songs Dataset

## Datensatzbeschreibung

Dieses Dataset enthält Informationen über die Top 50 Songs von Spotify in verschiedenen Ländern und Zeiträumen. Er umfasst 10 Felder: spotify_id (eindeutiger Bezeichner für jeden Song), name (Songtitel), artists (Interpreten), daily_rank (Position in den Top 50), daily_movement (Veränderung des Rangs im Vergleich zum Vortag), weekly_movement (Veränderung des Rangs im Vergleich zur Vorwoche), country (ISO-Code für das Land), snapshot_date (Datum der Datenerfassung), popularity (Spotifys Mass für die Popularität des Songs auf einer Skala von 0-100) und is_explicit (ob der Song explizite Texte enthält). Der vollständige Datensatz enthält über 1,7 Millionen Einträge von Oktober 2023 bis Februar 2025 (Ich habe das Set auf 50 Tausend Einträge verkürzt), die die Popularitätstrends auf den globalen Musikmärkten verfolgen. 

## Überlegungen zum Datenschutz

Der Spotify Top 50-Datensatz enthält keine persönlichen Nutzer- oder Hörerdaten, sondern nur aggregierte Popularitätskennzahlen zu Songs, die auf einer öffentlichen Plattform verfügbar sind. Alle Informationen in diesem Datensatz wurden aus öffentlich zugänglichen Spotify-Charts und API-Daten abgeleitet. Künstlernamen und Songtitel sind bereits öffentlich bekannt, und es sind keine privaten Hörgewohnheiten oder persönlich identifizierbaren Informationen enthalten. Der Datensatz folgt den Grundsätzen der fairen Nutzung für Forschungszwecke und steht mit den Nutzungsbedingungen für Entwickler von Spotify bezüglich öffentlich zugänglicher Chartdaten.

## Datensatzfelder

- **spotify_id**: Eindeutiger Bezeichner für den Song in Spotify
- **Name**: Der Titel des Songs
- **artists**: Name(n) des/der Künstler(s), der/die mit dem Lied verbunden ist/sind
- **täglicher_rang**: Täglicher Rang des Liedes in der Top-50-Liste
- **daily_movement**: Veränderung der Platzierung im Vergleich zum Vortag
- **wöchentliche_Bewegung**: Veränderung der Rangliste im Vergleich zur Vorwoche
- **country**: ISO-Code des Landes der Top 50 Playlist
- **snapshot_date**: Datum, an dem die Daten von Spotify erfasst wurden
- **Popularität**: Maß für die aktuelle Popularität des Songs auf Spotify (0-100)
- **ist_explizit**: Ob der Song explizite Lyrics enthält (True/False)


## Verwendung

Dieser Datensatz kann verwendet werden für:
- Analyse von Trends in der Musikpopularität über verschiedene Länder hinweg
- Untersuchung von saisonalen Schwankungen in den Musikpräferenzen
- Verfolgung der Leistung von Künstlern in den Charts im Laufe der Zeit
