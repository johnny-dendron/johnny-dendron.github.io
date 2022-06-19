---
id: 59neyh91x5bw954epzq1rbg
title: Schemas
desc: ""
updated: 1655665024447
created: 1655654866529
---

> Filetype is xxx**.yml**

## Video Documentation

[[https://youtu.be/nfvx8rv77NA?t=3140]]

[[Dendron wiki article|https://wiki.dendron.so/notes/c5e5adde-5459-409b-b34d-a0d75cbb1052/]]

> Schema help you apply consistent structure to all your notes.
>
> As you end up creating more notes, it can be hard to manage them at scale. Think of schemas as an optional type system for your notes that describe the hierarchy of your data and are represented as a hierarchy, themselves.

Schemas are written in [[Yaml|software.yaml]].

```
version: 1
schemas:

# this will match "cli.\*" notes

- id: cli
  # human readable description of hierarchy
  desc: command line interface reference
  # add this to the domain of your schema hierarchy
  parent: root
  # when a schema is a namespace, it can have arbitrary children. equivalent to cli.\* glob pattern
  namespace: true
  children:
  - cmd
  - env

# will match cli.\*.env

- id: env
  desc: cli specific env variables

# will match cli._.cmd._

- id: cmd
  desc: subcommands
  namespace: true

```

## Tags

#Dendron, #Software, #Yaml
