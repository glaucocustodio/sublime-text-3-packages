## Restoring packages

- Install ST3
- Navigate to Packages dir (usually `/Users/user/Library/Application Support/Sublime Text 3/Packages`)
- `rm -rf User`
- `git clone https://github.com/glaucocustodio/sublime-text-3-packages User`
- Open ST3 and install Package Control
- Wait some seconds (the packages will be downloaded)

## Overwriting ST settings (increase sidebar font and row padding)

- Open Command Palette (cmd+shift+p)
- Search for: `PackageResourceViewer: OpenResource`
- Choose `Theme - Default User`
- Choose `Default.sublime-theme`
- Look for `sidebar_label`, add `"font.size": 17` below `“color”`
- Look for `sidebar_tree`, set `"row_padding": [16, 12, 16, 3]`

## Packages

- <a target="_blank" href="https://sublime.wbond.net/packages/Better%20RSpec">Better RSpec</a>
- <a target="_blank" href="https://packagecontrol.io/packages/Better%20CoffeeScript">Better CoffeeScript</a>
- <a target="_blank" href="https://sublime.wbond.net/packages/Color%20Highlighter">Color Highlighter</a>
- <a target="_blank" href="https://packagecontrol.io/packages/CTags">CTags</a>
- <a target="_blank" href="https://sublime.wbond.net/packages/GitGutter">Git​Gutter</a>
- <a target="_blank" href="https://packagecontrol.io/packages/PackageResourceViewer">PackageResourceViewer</a>
- <a target="_blank" href="https://packagecontrol.io/packages/Sass">Sass</a>
- <a target="_blank" href="https://sublime.wbond.net/packages/SideBarEnhancements">Side​Bar​Enhancements</a>
