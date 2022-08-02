---
UI: true
arguments:
- QueuePosition [number]
invoke: ':'
memberOf: City
methodname: GetAt
returns:
- QueueEntry [table]
script: false
tags:
- City/CityBuildQueue/_function
- function/UI
title: CityBuildQueue.GetAt
---
# CityBuildQueue:GetAt
> this function is a member of [CityBuildQueue](civ-6/lua/CityBuildQueue.md)
> this method expects an implicit "self" argument. invoke it with `:`
-----
## Usage
|  UI | Script | Returns | Function | Arguments |
|:---:|:------:|-------:|:--------:|:---------|
|✓| |`QueueEntry [table]`|CityBuildQueue:GetAt|`QueuePosition [number]`|
