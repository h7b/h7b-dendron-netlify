This is an Obsidian Dataview query page, served for personal test purpose

```dataview
TABLE category, topic, year-of-publication, related
FROM "vault"
WHERE category != null
SORT category, topic, year-of-publication, related ASC
LIMIT 200
```
