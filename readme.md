# Notepad++ Markdown Highlighting

(Please note, the following and the CSS file were from the original project, and I have not yet modified them to reflect the stylistic changes I made. Feel free to look at the [branch indicating the original](../../tree/original) for the earlier styling or use mine.)

## Colors

This style uses Bespin (light on dark) colors. You'll probably have to do some color editing to make it fit your chosen theme -- unfortunately user defined language styles can't inherit colors from their parent theme.

## Style Guide

Because of limits of the generic Notepad++ user defined language lexer, highlighting is partial and a little buggy. But you can still get a lot out of it if you follow some simple style rules:

  + Use the `#` syntax for headers, not underlines. You can use underlines but they won't style the headings.
  + Remember `*`, `_`, and `>` only highlight the first word they've marked down.
  + Use `+` / `-` for lists, or change it in the dialog to dashes. Asterisks will conflict with emphasis highlighting.
  + Horizontal rules should be 3 or more dashes.
  + Nothing works if you start or end it inside a word.
  + Remember there's no highlighting for indentation/\<pre\> tags.
  
## How to use

  1. Open `%APPDATA%\Notepad++` (i.e., `C:\Users\[user]\AppData\Roaming\Notepad++`)
  2. Replace your `userDefineLang.xml` with the one in this repo, or add the contents of this `userDefineLang.xml` to the end of your current one.
  3. Restart Notepad++.
  4. Markdown highlighting will now automatically apply to `.markdown`,  `.mkdn`, `.mkd`, and `.md` files, or you can manually select it from the bottom of the "Language" menu.
  
## Extra nerdity

  If you like the way this highlighter looks so much you want to read everything in it, there's a css file that lets you do just that. 
