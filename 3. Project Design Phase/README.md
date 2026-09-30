# CRICKSTATS - Project Design Phase

## Data Model
- Player (custom object): player details plus roll-up summary fields
- Match Performance (custom object): one record per player per match

## Relationship
Match Performance has a Master-Detail relationship to Player, so roll-up summary fields on Player add up the Match Performance records.

## Interface
- CRICKSTATS Lightning App with Players, Match Performances, Reports, Dashboards and Home tabs
- Player Flow on the Home page
