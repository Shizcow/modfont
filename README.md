# modfont

A simple command line tool to insert glyphs into fonts, using python and fontforge.

For full usage, see `modFont --help`

## Example
To add two glyphs at specific unicode codepoint locations:
```
./modFont /usr/share/fonts/awesome-terminal-fonts/fontawesome-regular.ttf -p f2ee Outlook.com_icon.svg -p f2ea ethernet-solid.svg -o /usr/share/fonts/awesome-terminal-fonts/fontawesome-regular.ttf
```