# MDmap

MDmap is my working title for a free markdown-based mind map project. To start, I'll use [mermaid](https://mermaid.js.org/syntax/mindmap.html). Because it's available immediately in GitHub. I'm aware of [markmap](https://markmap.js.org/). But I haven't investigated it, or any other alternatives. Because that is beyond my current scope for this project.

Note that this is a learning project for me. Which means that I'm using it to gain practical experience of developing free mindmaps using mermaid markdown in this free GitHub repository. So it is not a complete guide. Though I hope I can develop it into one. Complete with examples and usable templates.

## MDmap Purpose & Scope

My immediate purpose is to find an alternative for MindMup. Because I no longer want to pay for its premium features. Noting that it is great value for commercial projects. But, in retirement, I'm looking for free options for all my Internet services.

To that end, my scope starts with looking at all my use cases for MindMup. Then assessing if these can be converted to MDmap. But prior to that, I will summarize [mermaid](https://mermaid.js.org/syntax/mindmap.html) for:

- Syntax
- Shapes
- Icons
- Classes
- Markdown Strings

If I can use MDmap for all my use cases, I will then consider if I can integrate it into Shrewdies.com. Or a separate mdmap.shrewdies.com project.

## MDmap Example

```mermaid
mindmap
MDmap
  Syntax
    Simply indent for next level
    Or add siblings at same level
        TODO: I haven't yet tested if there is a limit to number of levels
  Shapes
    [Square]
    (Rounded Square)
    ((Circle))
    ))Bang((
    )Cloud(
    {{Hexagon}}
    Default
  Icons
    A
    ::icon(fa fa-book)
    B(B)
    ::icon(mdi mdi-skull-outline)
    TODO: Research icon library integration if this feature is important. Otherwise, ignore for now. 
  Classes
    TODO: CSS classes need to be supplied by the site administrator
  Markdown Strings
    Are wrapped in shape+double quotes
        But I find this confusing.
        Because **markdown**, *word wrap*, and unicode seem to work on normal nodes.
    ["`Double asterisks for **bold**`"]
    ("Single asterisks for *italic*")
    ["Very long lines of text will automatically wrap. And text can also include unicode characters. Such as ⓵, ⓶, ⓷. Which might reduce the need to integrate icon libraries. Though those libraries obviously give more characters."]
    TODO: Check if markdown also works for:
        Links
        Images
        Tables
        Lists
            (Probably not because lists get set as nodes)
        HTML
```

## MDmap Icon 

```mermaid
mindmap
MDmap
  (MD)
   (m)
   (a)
   (p)
```

## MDmap Starter

```mermaid
mindmap
__UpdateThis_RootName__
  __UpdateThis_Child1__
   __UpdateThis_GrandChild1__
   __UpdateThis_GrandChild2__
  __UpdateThis_Child2__
```

## MDmap Potential Issues

```mermaid
mindmap
Potential Issues
  No node positioning
    But nodes could be numbered
    And Shapes could indicate:
        [Question]
            (Answer)
        [Problem]
            {{Potential Solution a}}
            {{Potential Solution b}}
```

## MDmap Action Plan

```mermaid
mindmap
MDmap Action Plan
  ⓵ Complete this overview
    TODO:consider other diagrams available in mermaid
  ⓷ Create a site for *Cloudflare Pages*
    Web2 or Web3?
  ⓸ Move each **mindmap** to its own page
  ⓶ Do a map from a markdown guide to test all features
  ⓹ Work on my Use Cases
```

## MindMup Use Cases

```mermaid
mindmap
MindMup Use Cases
  Snippets
  Organizing categories & sub categories
  Tracking status changes
```
