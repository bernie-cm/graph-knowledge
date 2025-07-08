## Use-Case Matrix

|#| User Story (Who/What/Why) | Impact (1-5) | Effort (1-5) | Acceptance Criteria |
|---|---|---|---|---|
|1| As an air traffic controller, I want to see all aircraft entering a specific sector so that I can anticipate conflicts. | 3 | 5 | Graph/REST query returns ICAO24 + entry-time in < 1 s for 95th pctl. | 
|2| As a maritime analyst, I want to see all vessels in a specific region to study traffic patterns. | 3 | 5 | REST query return mmsi in < 1 s for 95th pctl. |
|3| As an air traffic controller or maritime analyst, I want to explore all aircraft and vessels flagged to a specific country for analytical purposes. | 2 | 3 | REST query return aircraft and vessels with correct country in < 2 s for 90th pctl.|
|4| As an analyst, I want to create new entities using manual associations between other entities. | 1 | 1 |REST query creates a new entity with correct fields without fail.|
|5| As an analyst, I want to edit existing knowledge about aircraft and vessels. | 1 | 1 |The Graph should allow edits without fail.|
