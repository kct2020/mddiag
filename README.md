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

[240613 edit] On reflection, I prefer the MDmap.Shrewdies.com approach with a #BuildInPublic mindset. Using the Hive Blockchain to store MDmaps. Presented by my own mermaid-enabled frontend. However, this raises privacy issues as blockchain data is public. And encrypting it seems like overkill. So, I've added this as a potential issue.

## MDmap Example

```mermaid
%%{init: {"theme": "forest", "securityLevel": "loose" }}%%
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
  240420 No node positioning
    But nodes could be numbered (or dated)
    And Shapes could indicate:
        [Question]
            (Answer)
        [Problem]
            {{Potential Solution a}}
            {{Potential Solution b}}
  240613 Privacy of Web3 Version
    The Hive Blockchain presentation option is only one way of using MDmaps. So it is easy to maintain a private GitHub repo like this for private maps.
```

## MDmap Action Plan 240420

```mermaid
mindmap
MDmap Action Plan
  ⓵ Complete this overview
    TODO:consider other diagrams available in mermaid
  ⓷ Create a site for *Cloudflare Pages*
    Web2 or Web3? (see <a href='https://github.com/kct2020/mdmap?tab=readme-ov-file#mdmap-potential-issues'>Potential Issues</a>)
  ⓸ Move each **mindmap** to its own page
  ⓶ Do a map from a markdown guide to test all features
  ⓹ Work on my Use Cases
```

## MDmap Action Plan 240613

```mermaid
mindmap
MDmap Action Plan
  ⓷ Research new pages
    Include other diagrams available in mermaid. Especially those listed as probably supporting links
    Investigate options available for
      mermaid align, zoom
      Double% directive that seems to be overriding https://mermaid.js.org/config/setup/modules/mermaidAPI.html?#mermaidapi-configuration-defaults
  ⓶ Create a site for *Cloudflare Pages*
    Web2 or Web3? See 'https://github.com/kct2020/mdmap?tab=readme-ov-file#mdmap-potential-issues' Potential Issues
    Experiment with logo using different themes
    Consider changing name to MDdiag
  ⓵ Move each **mindmap** to its own page as current page is getting too big and confusing
  ⓹ Do a map from a markdown guide to test all features
  ⓸ Work on my Public Use Cases
    Common unicode characters (https://www.amp-what.com/unicode/search/double%20circled 1-10)
    Useful Hypothesis snippets
    Hive posting snippets
  ⓺ Work on my Private Use Cases, with public examples as personal templates
    Work in progress notes
    Life/Financial plans
```

## MindMup Use Cases

```mermaid
mindmap
MindMup Use Cases
  Snippets
  Organizing categories & sub categories
  Tracking status changes
```
