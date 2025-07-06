## Data Field Cheat-Sheet

| Domain | Field | Example value | Source feed | Needed for | Notes |
|---|---|---|---|---|---|
| Aircraft | icao24 | 7C6B07 | ADS-B | unique ID | becomes PK in graph |
| Aircraft | registration | N123AB | ADS-B | plotting | |
| Aircraft | model | A320 | ADS-B | Basic aircraft type | |
| Aircraft | manufacturer | Boeing | ADS-B | Aircraft information | |
| Aircraft | countryOfRegistration | Australia | ADS-B | Flag state for legal context | ISO 2-letter code or full name |
| Vessel | imoNumber | 9074729 | AIS Hub | unique ID | seven-digit unique identifier<br>International Maritime Organization number - Crucial unique, permanent identifier |
| Vessel | mmsi | 235109000 | AIS Hub | | This is a 9-digit number, starting with the MID for the flag state |
| Vessel | vesselName | OCEAN EXPLORER | AIS Hub | | |
| Vessel | vesselType | Container Ship | AIS Hub | | |
| Vessel | flagState | United Kingdom | AIS Hub | | |
