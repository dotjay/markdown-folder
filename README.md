# markdown-folder package

Atom package that folds and unfolds markdown headings.

Note that the headings must use the hash signs. That is, underlining with equal signs does not work.
There must also be some whitespace between the hash sign and the heading text. Examples that DO work:

`# My First Heading`

`## My Second Heading`

Commands:
  * 'markdown-folder:toggle': =>: => Fold/unfold heading at cursor
  * 'markdown-folder:unfoldall':: => Unfold all headings
  * 'markdown-folder:cycle': =>: => Cycle heading at cursor (Collapse all - show headings - show all)
  * 'markdown-folder:cycleall': =>: => Cycle all h1 headings
  * 'markdown-folder:unfoldall':: => Unfold all headings
  * 'markdown-folder:foldall-h1': => Fold all h1 headings
  * 'markdown-folder:foldall-h2': => Fold all h2 headings
  * 'markdown-folder:foldall-h3': => Fold all h3 headings
  * 'markdown-folder:foldall-h4': => Fold all h4 headings
  * 'markdown-folder:foldall-h5': => Fold all h5 headings


Suggested bindings (not implemented, use in your personal settings if you like):
```
'atom-workspace':
  'alt-t': 'markdown-folder:toggle'
  'ctrl-alt-t': 'markdown-folder:unfoldall'
  'alt-c': 'markdown-folder:cycle'
  'ctrl-alt-t': 'markdown-folder:cycleall'
  'ctrl-alt-1': 'markdown-folder:foldall-h1'
  'ctrl-alt-2': 'markdown-folder:foldall-h2'
  'ctrl-alt-3': 'markdown-folder:foldall-h3'
  'ctrl-alt-4': 'markdown-folder:foldall-h4'
  'ctrl-alt-5': 'markdown-folder:foldall-h5'
```
