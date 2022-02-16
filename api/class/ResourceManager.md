---
title: ResourceManager
description: Responsible for creating and resolving resources such as images and sounds.
published: 1
date: 2022-02-16T11:31:01.161Z
tags: api, class, singleton
editor: markdown
dateCreated: 2022-02-15T20:55:35.113Z
---

# Examples
## Loading an Image
### C#
```cs
IGraphicsResource image = Singletons.ResourceManager.ResolveImage("https://i.imgur.com/OncH4A5.jpeg")
```
### Lua
```lua
--pending validation
local image = singletons.ResourceManager:ResolveImage("https://i.imgur.com/OncH4A5.jpeg")
```

# Methods
## ResolveImage
[<kbd>GraphicsResource</kbd>](/api/class/GraphicsResource) `ResolveImage(string identifier)`
Returns a [GraphicsResource](/api/class/GraphicsResource) or null on failure