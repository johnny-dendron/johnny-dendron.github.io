---
id: m49jk5x6xk7lu7txg1cocza
title: Dendron Yml
desc: ""
updated: 1656259933560
created: 1656259878734
---

```
version: 5
dev:
    enablePreviewV2: true
    enableSelfContainedVaults: true
commands:
    lookup:
        note:
            selectionMode: extract
            confirmVaultOnCreate: true
            vaultSelectionModeOnCreate: smart
            leaveTrace: true
            bubbleUpCreateNew: true
            fuzzThreshold: 0.2
    randomNote: {}
    insertNote:
        initialValue: templates
    insertNoteLink:
        aliasMode: none
        enableMultiSelect: false
    insertNoteIndex:
        enableMarker: false
    copyNoteLink: {}
    templateHierarchy: template
workspace:
    vaults:
        -
            fsPath: .
            selfContained: true
            name: MyDendron
    journal:
        dailyDomain: daily
        name: journal
        dateFormat: y.MM.dd
        addBehavior: childOfDomain
    scratch:
        name: scratch
        dateFormat: y.MM.dd.HHmmss
        addBehavior: asOwnDomain
    task:
        name: task
        dateFormat: y.MM.dd
        addBehavior: asOwnDomain
        statusSymbols:
            '': ' '
            wip: w
            done: x
            assigned: a
            moved: m
            blocked: b
            delegated: l
            dropped: d
            pending: 'y'
        taskCompleteStatus:
            - done
            - x
        prioritySymbols:
            H: high
            M: medium
            L: low
        todoIntegration: false
        createTaskSelectionType: selection2link
    graph:
        zoomSpeed: 1
        createStub: true
    enableAutoCreateOnDefinition: true
    enableHandlebarTemplates: false
    enableXVaultWikiLink: false
    enableRemoteVaultInit: true
    enableUserTags: true
    enableHashTags: true
    workspaceVaultSyncMode: noCommit
    enableAutoFoldFrontmatter: false
    enableEditorDecorations: true
    maxPreviewsCached: 10
    maxNoteLength: 204800
    enableFullHierarchyNoteTitle: false
    templateHierarchy: template
preview:
    enableFMTitle: true
    enableNoteTitleForLink: true
    enableFrontmatterTags: true
    enableHashesForFMTags: false
    enableMermaid: true
    enablePrettyRefs: true
    enableKatex: true
    automaticallyShowPreview: true
publishing:
    enableFMTitle: true
    enableNoteTitleForLink: true
    enableMermaid: true
    enablePrettyRefs: true
    enableKatex: true
    copyAssets: true
    siteHierarchies:
        - root
    writeStubs: false
    siteRootDir: docs
    seo:
        title: Dendron
        description: Personal Knowledge Space
    github:
        enableEditLink: true
        editLinkText: Edit this page on GitHub
        editBranch: main
        editViewMode: tree
    enableSiteLastModified: true
    enableFrontmatterTags: true
    enableHashesForFMTags: false
    enableRandomlyColoredTags: true
    enableTaskNotes: true
    enablePrettyLinks: true

```
