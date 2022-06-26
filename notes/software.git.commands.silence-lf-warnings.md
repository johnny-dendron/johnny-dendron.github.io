---
id: wjr7f8t2ug44nc7w67ra7oe
title: Silence Lf Warnings
desc: ""
updated: 1656279965865
created: 1656279866228
---

Turn turn off lines like:

```
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in notes/world.countries.us.states.wa.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in notes/world.countries.us.states....
```

By opening a bash terminal and entering:

`git config --global core.safecrlf false`
