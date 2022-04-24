---
id: 7sslhg74atqkq6rm7nw5m2p
title: Logseq
desc: ''
updated: 1650834768772
created: 1650671611497
---
# Logseq - How do I use

## Overview

[Logseq](https://logseq.com/) is a note-taking tool, free and open source alternative of [Roam Research](https://roamresearch.com/)

Difficulty to use: 2/5

Thoughts:
- notes are saved locally as plaintext markdown files
- It also has spaced repetition flashcards feature.

A sketch of the current UI. *Credit*: [danzu](https://discord.com/channels/725182569297215569/756886540038438992/940821337449046097) in Logseq discord
![logseq-ui](https://ik.imagekit.io/casa/h7b-dendron/2022-02-11_logseq-UI_zj-UxZtBZ.png?ik-sdk-version=javascript-1.4.3&updatedAt=1644592013237){max-width: 300px, display: block, margin: 0 auto}

## Publishing

- Publishing with Logseq app on desktop via `export public pages` feature:
    - tutorial at [here](https://logseq.github.io/#/page/Publishing%20(Desktop%20App%20Only))
    - Pricing: free
    - this feature simply bundles the whole Logseq web app with your public pages and let you deploy them as a static website
    - deploy to anywhere supporting static hosting, like GitHub Pages, Netlify, Vercel
    - [demo page](https://docs.logseq.com/#/page/Contents)
- [Logseq Publish](https://github.com/logseq/publish)
    - a tool that generates a fast, SEO-friendly, and scalable website from your Logseq content
    - output assets code size is smaller than `export public pages` feature on Desktop App
    - Pricing: free
    - deploy to anywhere supporting static hosting, like GitHub Pages, Netlify, Vercel
    - [demo page](https://eloquent-keller-6512b6.netlify.app/)
- [Logseg Publish Action](https://github.com/marketplace/actions/logseq-publish)
    - [document](https://pengx17.github.io/knowledge-garden/#/page/logseq%20publish%20github%20action) written by author, that explains what does this GitHub Action do
    - thoughts: I don't understand, just put here and turn back to investigate later when I have much more interest with Logseq
- [logseq Schrödinger](https://github.com/sawhney17/logseq-schrodinger) community plugin for Logseq
    - a plugin that export Logseq pages to [Hugo](https://gohugo.io/) static site
    - you first build the Hugo website and then drag the contents of the export to the contents folder in Hugo. The plugin doesn't create a website, it formats Logseq pages to the format accepted by Hugo for posts


## Related resources

- [Three Choices New Users Need to Make](https://discuss.logseq.com/t/three-choices-new-users-need-to-make/3411)
    - an article explaining three dilemmas that beginner will experience with Logseq in their first try which are
        - why should I use daily journal
        - tags, hierarchy, page-tags, which one should I use
        - one graph for everything or multiple graphs. This is similar to the question should I use one vault or multiple vault in Dendron or Obsidian