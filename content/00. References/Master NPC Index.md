```dataview  
TABLE Race, Occupation, Location, Faction  
FROM #npc
WHERE status = "Alive"  
SORT file.name ASC  
```