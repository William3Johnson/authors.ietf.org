---
title: RFCXML Elements
description: 
published: true
date: 2021-11-02T23:19:03.877Z
tags: 
editor: markdown
dateCreated: 2021-11-02T22:58:38.001Z
---


## `<abstract>`
## Tabs {.tabset}

### Usage
Contains the Abstract of the document. See RFC7322 for more information on restrictions for the Abstract.
### Schema
Parents: `<front>`

Contents: (`dl`, `ol`, `t`, `ul`)+

### `"anchor"`

Document-wide unique identifier for this `<abstract>` element.

## `<address>`

Provides address information for the author.

Parents: `<author>`, `<contact>`

Children: `<postal>`, `<phone>`, `<email>`, <uri?