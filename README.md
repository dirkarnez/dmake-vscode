dmake-vscode
============
### Notes
- `git clone` and work directly in extensions folder (`--extensions-dir %EXTENSION_PATH%`), however
    - networked symbolic link does not work (`mklink /j "target" "real_location"` on local drives maybe work)
    - networkless directory shortcut (with extension `.lnk`) does not work - get filtered out

### TODOs
- [ ] Attributes
- [ ] Custom elements by class
- [ ] Code blocks

### References
- [**vscode/html.tmLanguage.json at main · microsoft/vscode · GitHub**](https://github.com/Microsoft/vscode/blob/main/extensions/html/syntaxes/html.tmLanguage.json)
- [**Language Grammars — TextMate 1.x Manual**](https://macromates.com/manual/en/language_grammars)
