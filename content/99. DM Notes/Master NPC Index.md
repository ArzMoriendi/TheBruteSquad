```dataview  
TABLE race, occupation, location, faction  
FROM #npc  
WHERE status = "alive"  
SORT file.name ASC  
```