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

## Add to path (macOS)

`ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl`

## Shortcuts

- `super+i`: run macro `inline_block_converter`
- `ctrl+shift+r`: `bundle exec rspec $file` for rspec files and `bundle exec m $file` for ruby files
- `ctrl+s`: reveal file in side bar
- `ctrl+c`: copy relative path of the current file to the clipboard
- `ctrl+x`: navigate to definition (ctags)
- `ctrl+z`: return to previous definition (ctags)

## Packages

- <a target="_blank" href="https://sublime.wbond.net/packages/ApplySyntax">ApplySyntax</a>
- <a target="_blank" href="https://packagecontrol.io/packages/Better%20CoffeeScript">Better CoffeeScript</a>
- <a target="_blank" href="https://packagecontrol.io/packages/Case%20Conversion">Case Conversion</a>
- <a target="_blank" href="https://sublime.wbond.net/packages/Color%20Highlight">Color Highlight</a>
- <a target="_blank" href="https://packagecontrol.io/packages/Copy%20Relative%20Path">Copy Relative Path</a> (`ctrl+c` to copy relative path to clipboard)
- <a target="_blank" href="https://packagecontrol.io/packages/CTags">CTags</a>
- <a target="_blank" href="https://packagecontrol.io/packages/Elixir">Elixir</a>
- <a target="_blank" href="https://packagecontrol.io/packages/Emmet">Emmet</a>
- <a target="_blank" href="https://sublime.wbond.net/packages/GitGutter">Git​Gutter</a>
- <a target="_blank" href="https://sublime.wbond.net/packages/Haml">Haml</a>
- <a target="_blank" href="https://packagecontrol.io/packages/PackageResourceViewer">PackageResourceViewer</a>
- <a target="_blank" href="https://packagecontrol.io/packages/Pretty%20JSON">Pretty JSON</a>
- ~~<a target="_blank" href="https://packagecontrol.io/packages/RainbowBrackets">RainbowBrackets</a>~~
- <a target="_blank" href="https://packagecontrol.io/packages/rainbow_csv">rainbow_csv</a>
- <a target="_blank" href="https://packagecontrol.io/packages/RSpec%20Buddy">RSpec Buddy</a>
- <a target="_blank" href="https://packagecontrol.io/packages/SCSS">SCSS</a>
- <a target="_blank" href="https://packagecontrol.io/packages/Select%20Quoted">Select Quoted</a>
- <a target="_blank" href="https://packagecontrol.io/packages/SendCode">SendCode</a> (`ctrl+shift+r` to test the current open file)
- <a target="_blank" href="https://sublime.wbond.net/packages/SideBarEnhancements">Side​Bar​Enhancements</a>
- <a target="_blank" href="https://packagecontrol.io/packages/Solarized%20Color%20Scheme">Solarized Color Scheme</a>
- <a target="_blank" href="https://sublime.wbond.net/packages/TypeScript">TypeScript</a>
