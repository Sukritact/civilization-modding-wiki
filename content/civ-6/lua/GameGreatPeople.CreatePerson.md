---
UI: false
arguments:
- PlayerID [number]
- IndividualID [number]
- X [number]
- Y [number]
invoke: ':'
memberOf: Game
methodname: CreatePerson
returns: []
script: true
tags:
- Game/GameGreatPeople/_function
- function/script
title: GameGreatPeople.CreatePerson
---
# GameGreatPeople:CreatePerson
> this function is a member of [GameGreatPeople](civ-6/lua/GameGreatPeople.md)
> this method expects an implicit "self" argument. invoke it with `:`
-----
## Usage
|  UI | Script | Returns | Function | Arguments |
|:---:|:------:|-------:|:--------:|:---------|
| |✓||GameGreatPeople:CreatePerson|`PlayerID [number]`<br>`IndividualID [number]`<br>`X [number]`<br>`Y [number]`|

## Notes
  
Creates the specified Great Person Individual. Units created this way will stack on the specified tile with no limit.  
  
Great Person Recruitment history is not updated, and it does not seem to prevent the same Great Person Individual from being earned normally through gameplay. This contrasts with [GameGreatPeople.GrantPerson](civ-6/lua/GameGreatPeople.GrantPerson.md) which does.  
  
### Parameters  
- `playerID [number]`  
- `IndividualID [number]`   
    - Corresponds to a an `Index` or `Hash` column in the [`GreatPersonIndividuals`](civ-6/database/GreatPersonIndividuals.md) table  
- `X [number]`  
- `Y [number]