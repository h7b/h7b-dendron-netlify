---
id: CroxQVfNqCIcpUBNCgLaW
title: Calculation in Txt Editor
desc: ''
updated: 1654244015552
created: 1635893931967
---
# Implement inline calculations in text editor

## VS Code plugin
- [Qalc (by nortakales)](https://marketplace.visualstudio.com/items?itemName=nortakales.vs-qalc), [Mathpad](https://marketplace.visualstudio.com/items?itemName=sagebind.mathpad)
    - Note for both `Mathpad` and `Qalc (by nortakales)`:
        - calculations need to be separated by each line. Cannot combine text with formula in the same line.
        - outputs are updated automatically with changes of inputs
        - results of calculation are rendered separately at the end of the line. And they are not part of markdown file. It means that you don't see the results if you use another app like `Sublime Text` to read the markdown file
- [Qalc (by Thea Flowers)](https://marketplace.visualstudio.com/items?itemName=TheaFlowers.qalc)
    - must download the companion app [Qalculate!](http://qalculate.github.io/downloads.html)
    - have to run command manually on the current selection / line through `command palette` or shortcut `Ctrl + Shift + /`
    - results of calculations are written in the markdown file

## Obsidian plugin
- Meld Calc ![[notes.tutorial.obsidian-md.plugins.meld-calc#obsidian-calculator-aka-meld-calc,1:#*]]

## Coda
- In [coda](https://coda.io/), you can 
    - embedded inline calculation using [math formula](https://coda.io/formulas#AbsoluteValue)
    - also assign variable or placeholder, and use it within inline formula, as depicted in this [community post](https://community.coda.io/t/variable-or-placeholder/15162/2).
        - example: i have a table, where `value` column is formatted as `number`

        | variable | value |
        |----------|-------|
        | x        | 2     |
        | y        | 3     |
        
        With the text <br>
        `The sum of x and y is =sum(x.value,y.value)` <br>
        The output will be <br>
        `The sum of x and y is 5` <br>
        When we modify the number in column `value`, the output will change synchronously

## Standalone webapp
- [reactivepad](https://reactivepad.com/)
- [Math Notepad](https://mathnotepad.com/)
- [Blockpad](https://blockpad.net/)
- [Livedocs](https://livedocs.com/)
    - [Hacker News discussion](https://news.ycombinator.com/item?id=30735058)
    - [Pricing](https://livedocs.com/pricing) starts at USD 30/month, with 14-day trial only
    - create interactive document with live data
- [Patera](https://patera.io/)
    - embed variables, calculations in dynamic interactive documents
- [[Grid|notes.tutorial.tools-spreadsheet-alternatives#grid]]