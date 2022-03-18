This is an Obsidian Dataview query page, served for personal test purpose

```dataview
TABLE category AS "Category"
FROM "vault"
WHERE category != null
SORT category ASC
LIMIT 10
```

```dataview
TABLE topic AS "Topic" 
FROM "vault"
WHERE topic != null
SORT topic ASC
LIMIT 10
```

```dataview
TABLE year-of-publication AS "Year of Publication" 
FROM "vault"
WHERE year-of-publication != null
SORT year-of-publication ASC
LIMIT 10
```

```dataview
TABLE related AS "Related" 
FROM "vault"
SORT related DESC
LIMIT 20
```