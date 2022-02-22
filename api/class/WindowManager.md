---
title: WindowManager
description: 
published: 1
date: 2022-02-22T22:20:37.097Z
tags: api, class, singleton
editor: markdown
dateCreated: 2022-02-22T22:20:37.097Z
---

# Examples
## Creating the main window
### C#
```cs
var windowManager = Singletons.WindowManager;
var window = windowManager.CreateMainWindow("Window Title");
```

# Methods
## createMainWindow
[<kbd>DeviapWindow</kbd>](/api/class/DeviapWindow) `createMainWindow(string name)`
Returns a [DeviapWindow](/api/class/DeviapWindow) or null on failure
## getMainWindow
[<kbd>DeviapWindow</kbd>](/api/class/DeviapWindow) `createMainWindow()`
Returns a [DeviapWindow](/api/class/DeviapWindow)