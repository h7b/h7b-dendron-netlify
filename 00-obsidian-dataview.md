This is an Obsidian Dataview query page, served as an overview of vault's content

```dataview
TABLE category, topic, year-of-publication, related
FROM "vault"
WHERE category != null
SORT category, topic, year-of-publication, related ASC
LIMIT 200
```
