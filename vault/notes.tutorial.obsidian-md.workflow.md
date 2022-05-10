---
id: qvacktliy1b7kqnigmvewo1
title: Workflow
desc: ''
updated: 1652222880651
created: 1647820438689
---
# Typical workflow of Obsidian users

## Project note by `@zsviczian`

- Explanation clip on [Youtube](https://www.youtube.com/watch?v=qIKg_1FNUgk)
- Scripts on [GitHub](https://gist.github.com/zsviczian/fd3fcae4e2c4fa2be668756dca59da06)
- Thoughts: 
    - author has interesting way to transclude tasks, working notes, contacts from daily notes into topic and project
    - he uses [Templater](https://silentvoid13.github.io/Templater/) script to achieve some task automation

## Create link to local files/folder

- I can create a markdown link to a file or folder on my local system by holding `CTRL` and drag-drop the file/folder into Obsidian active note

## Use dataview to create connection from daily-note to person-note

- workflow by `dryice` in [Obsidian discord](https://discord.com/channels/686053708261228577/744933215063638183/972992393123102730)
- dataview query
    ````
    ```dataview
    TABLE 
        WITHOUT ID
        link(Source, dateformat(date(Source), "EEE d MMM yy")) as Date___, 
        rows.Comments as "Comments"
    FROM "Journal Folder"
    WHERE  contains(cmnt, this.file.name)
    FLATTEN cmnt as Comments
    WHERE contains(Comments, this.file.name)
    GROUP BY file.link as Source
    SORT rows.file.day desc
    ```
    ````
- demo: ![person-note](https://media.discordapp.net/attachments/744933215063638183/972992392368095252/unknown.png?width=1416&height=670){max-width: 300px, display: block, margin: 0 auto}