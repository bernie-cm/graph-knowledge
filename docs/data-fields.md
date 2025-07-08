## Data Field Cheat-Sheet

| Domain | Field | Example value | Source feed | Needed for (stories) | Notes |
|---|---|---|---|---|---|
| Aircraft | icao24 | 7C6B07 | ADS-B | unique ID | becomes PK in graph |
| Aircraft | registration | N123AB | ADS-B | User story 1-2-3 |None|
| Aircraft | model | A320 | ADS-B | Basic aircraft type | None |
| Aircraft | manufacturer | Boeing | ADS-B | Aircraft information | None |
| Aircraft | countryOfRegistration | Australia | ADS-B | Flag state for legal context | ISO 2-letter code or full name |
| Aircraft | latitude | -16.917 | ADS-B | 1,2 | — |
| Aircraft | longitude | 145.770 | ADS-B | 1,2 | — |
| Aircraft | baro_altitude | 11500 | ADS-B | 1 | metres |
| Aircraft | timestamp | 1720416570 | ADS-B | 1,2,3 | UNIX |
| Vessel | imoNumber | 9074729 | AIS Hub | unique ID | seven-digit unique identifier<br>International Maritime Organization number - Crucial unique, permanent identifier |
| Vessel | mmsi | 235109000 | AIS Hub | | This is a 9-digit number, starting with the MID for the flag state |
| Vessel | mmsi | 503123000 | AIS Hub | 2,3 | PK |
| Vessel | lat | -15.400 | AIS Hub | 2 | — |
| Vessel | lon | 130.550 | AIS Hub | 2 | — |
| Vessel | sog | 12.4 | AIS Hub | 2 | speed over ground (kn) |
| Vessel | timestamp | 1720416570 | AIS Hub | 2,3 | UNIX |
| Vessel | vesselName | OCEAN EXPLORER | AIS Hub | User story 3-4 | None |
| Vessel | vesselType | Container Ship | AIS Hub | User story 3-4 | None |
| Vessel | flagState | United Kingdom | AIS Hub | User story 3-4 |None |
