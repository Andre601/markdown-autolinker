# Markdown AutoLinker

Markdown AutoLinker is a Python-Markdown extension inspired by the `abbr` extension... In fact does it use the same code as said extension, with some minor changes:

- The syntax used is `.[text]: <link>` rather than `*[text]: <description>`
- Any matching text is replaced with a `a` tag, rather than a `abbr` tag

Despite these changes does original credit go to the Python-Markdown devs for their original code.