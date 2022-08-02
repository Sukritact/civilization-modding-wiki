---
UI: true
arguments:
- PlayerID [number]
- IndividualID [number]
- YieldType [number]
invoke: ':'
memberOf: Game
methodname: GetPatronizeCost
returns: []
script: true
tags:
- Game/GameGreatPeople/_function
- function/UI
- function/script
title: GameGreatPeople.GetPatronizeCost
---
# GameGreatPeople:GetPatronizeCost
> this function is a member of [GameGreatPeople](civ-6/lua/GameGreatPeople.md)
> this method expects an implicit "self" argument. invoke it with `:`
-----
## Usage
|  UI | Script | Returns | Function | Arguments |
|:---:|:------:|-------:|:--------:|:---------|
|✓|✓||GameGreatPeople:GetPatronizeCost|`PlayerID [number]`<br>`IndividualID [number]`<br>`YieldType [number]`|

## Notes
  
`YieldType [number]` corresponds to an entry in the `YieldTypes` global table, NOT the Index of the yield in the game database.

For instance, see this code sample:

> `pGreatPeople:GetPatronizeCost(displayPlayerID, entry.Individual, YieldTypes.GOLD)`

### Parameters
- `PlayerID [number]`
- `IndividualID [number]`
	- Corresponds to a an `Index` or `Hash` column in the [`GreatPersonIndividuals`](civ-6/database/GreatPersonIndividuals.md) table
- `YieldType [number]`
	- corresponds to an entry in the `YieldTypes` global table