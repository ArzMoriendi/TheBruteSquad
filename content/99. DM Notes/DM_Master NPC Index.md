
```dataview  
TABLE Race, Occupation, Location, Faction  
FROM #dm_npc
WHERE status = "Alive"  
SORT file.name ASC  
```