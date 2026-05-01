---
Tags:
  - npc
  - dnd
  - campaign
Type: NPC
Created: <% tp.date.now("YYYY-MM-DD") %>
Updated: <% tp.date.now("YYYY-MM-DD") %>
Race:
Occupation:
Location:
Faction:
Disposition:
Status:
---

# <% tp.file.title %>


> [!info] NPC Overview
> **Race:** {{race}}  
> **Gender / Identity:** {{gender}}  
> **Age:** {{age}}  
> **Occupation:** {{occupation}}  
> **Class / Type:** {{class_type}}  
> **Alignment:** {{alignment}}  
> **Location:** {{location}}  
> **Faction:** {{faction}}  
> **Status:** {{status}}

---

## Quick Summary

Write a short summary of who this NPC is and why they matter.

---

## Appearance

- **Height / Build:**  
- **Hair:**  
- **Eyes:**  
- **Distinct Features:**  
- **Clothing / Gear:**  
- **Voice / Accent:**  

---


# DM NOTES

> Remove this section from player-facing notes if desired.



## Personality

- **Traits:**  
- **Mannerisms:**  
- **Likes:**  
- **Dislikes:**  
- **Flaws:**  
- **Secrets:**  

---

## Background

Describe upbringing, career, major events, and current situation.

---

## Motivations

- Primary Goal:
- Secondary Goal:
- Fear:
- Desire:

---

## Relationships

### Family

| Name | Relation | Status | Notes |
|------|----------|--------|------|
| [[ ]] |  |  |  |

### Allies

| Name | Role | Notes |
|------|------|------|
| [[ ]] |  |  |

### Rivals / Enemies

| Name | Conflict | Notes |
|------|----------|------|
| [[ ]] |  |  |

---

## Knowledge

- Rumor:
- Secret:
- Local Information:
- Quest Hook:

---

## Inventory / Possessions

- 
- 
- 

---


## Encounter Notes

- **First Met:**  
- **Last Seen:**  
- **Party Opinion:**  
- **Current Status:** Alive / Dead / Missing / Unknown

---

## Linked Notes

- [[Locations]]
- [[Organizations]]
- [[Quest Log]]

## Dataview Notes

```dataview
TABLE race, occupation, location, faction, disposition, status
FROM #npc
WHERE file.name = this.file.name
```