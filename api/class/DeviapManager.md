---
title: DeviapManager
description: This singleton can be used by applications to locate relevant file paths and to end the running process.
published: 1
date: 2022-02-15T20:51:16.259Z
tags: class, api, singleton
editor: markdown
dateCreated: 2022-02-15T19:21:32.772Z
---

# Properties
## AppPath
<kbd>string</kbd> This is the directory that contains the running app's manifest file,
## AppDataDirectory
<kbd>string</kbd> A directory unique to this application.
## CSBindingsPath
<kbd>string</kbd> A dll file containing up to date C# bindings.
## WorkingDirectory
<kbd>string</kbd> The working directory (from where the CLI was used)

# Methods
## Quit
<kbd>void</kbd> `quit()`
Ends the currently running app