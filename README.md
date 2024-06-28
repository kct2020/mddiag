# MDdiag

MDdiag (formerly MDmap) is my working title for a free markdown-based mind map project. To start, I'll use [mermaid](https://mermaid.js.org/syntax/mindmap.html). Because it's available immediately in GitHub. I'm aware of [markmap](https://markmap.js.org/). But I haven't investigated it, or any other alternatives. Because that is beyond my current scope for this project.

Note that this is a learning project for me. Which means that I'm using it to gain practical experience of developing free mindmaps using mermaid markdown in this free GitHub repository. So it is not a complete guide. Though I hope I can develop it into one. Complete with examples and usable templates.

## MDdiag Purpose & Scope

My immediate purpose is to find an alternative for MindMup. Because I no longer want to pay for its premium features. Noting that it is great value for commercial projects. But, in retirement, I'm looking for free options for all my Internet services.

To that end, my scope starts with looking at all my use cases for MindMup. Then assessing if these can be converted to MDdiag. But prior to that, I will summarize [mermaid](https://mermaid.js.org/syntax/mindmap.html) for:

- Syntax
- Shapes
- Icons
- Classes
- Markdown Strings

If I can use MDdiag for all my use cases, I will then consider if I can integrate it into Shrewdies.com. Or a separate MDdiag.shrewdies.com project.

[240627 edit] On reflection, I prefer the MDdiag.Shrewdies.com approach with a #BuildInPublic mindset. Using the Hive Blockchain to store MDdiags. Presented by my own mermaid-enabled frontend. However, this raises privacy issues as blockchain data is public. And encrypting it seems like overkill. So, I've added this as a potential issue.

## MDdiag Example

```mermaid
%%{init: {"theme": "forest", "securityLevel": "loose" }}%%
mindmap
MDdiag
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
        But **markdown**, *word wrap*, and unicode seem to work on normal nodes. So this only seems relevant for wordwrap, and possibly for including HTML. 
    ["`Double asterisks for **bold**`"]
    ("Single asterisks for *italic*")
    ["Very long lines of text will automatically wrap. And text can also include unicode characters. Such as ⓵, ⓶, ⓷. Which might reduce the need to integrate icon libraries. Though those libraries obviously give more characters."]
    See how mindmap also works for:
        Links
          Links are not enabled for mindmap. Though there is a workround at https://github.com/mermaid-js/mermaid/issues/4152#issuecomment-1612670557 but maybe it's better to use a different mermaid diagram. Currently:
            classDiagram
            flowchart
            gantt
        Images
          ("`<img src='https://iconscout.com/ms-icon-310x310.png'; width='30' />`")
            [Doesn't work, but could be mermaid securityLevel issue. So retry on own website]
        Tables
          Test using HTML
              ["`<table>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
</table>`"]
          Test using Markdown
              ["`| Month    | Savings |
| -------- | ------- |
| January  | $250    |
| February | $80     |
| March    | $420    |`"]
        Lists
            (Probably not because lists get set as nodes)
              ["`<code>&hybull; However:
              &hybull; Markdown Strings
              &hybull; allow list structure
              &hybull; but need classes to align left</code>`"]
        HTML
          (Yes - used in Lists example)
            [But there are probably some exceptions]
```

## MDdiag Pages

- [](https://github.com/kct2020/mddiag/blob/main/)
- [MDdiag Icon](https://github.com/kct2020/mddiag/blob/main/mddiag-icon.md#mddiag-icon)
- [MDmap Starter](https://github.com/kct2020/mddiag/blob/main/mdmap-starter.md#mdmap-starter)
- [MDdiag Potential Issues](https://github.com/kct2020/mddiag/blob/main/mddiag-potential-issues.md#mddiag-potential-issues)
- [MDmap Action Plan 240420](https://github.com/kct2020/mddiag/blob/main/mdmap-action-plan-240420.md#mdmap-action-plan-240420)
- [MDdiag Action Plan 240627](https://github.com/kct2020/mddiag/blob/main/mddiag-action-plan-240627.md#mddiag-action-plan-240627)
- [MDdiag Action Plan 240628](https://github.com/kct2020/mddiag/blob/main/mddiag-action-plan-240627.md#mddiag-action-plan-240628)
- [MDdiag Overview](https://github.com/kct2020/mddiag/blob/main/mindmup-overview.md#mindmup-overview)
- [MindMup Use Cases](https://github.com/kct2020/mddiag/blob/main/mindmup-use-cases.md#mindmup-use-cases)
