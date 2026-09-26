# Contributing

Thanks for wanting to help with the **Jagged Alliance 2 Game Editor**! It is a free tool made by fans, for fans, and every bug report, idea and fix makes it better.

## Reporting a bug

The quickest way: in the editor open **⚙ → Report a problem…**. It packs what happened, the version, the editor's log and (if you tick them) the open save, map and `Ja2_Options.INI` into one `.zip` and opens the Issues page — attach the `.zip` to a new issue.

Or open an [issue](../../issues) by hand and include:

- the editor version and your game version (and any mods you use, e.g. 1.13 build from `JA2_113-Version.txt`);
- what you did, what you expected and what happened instead;
- a screenshot, and the save or data file if the problem is with one (zip it if it is large).

Please search the [open issues](../../issues) first — maybe it is already reported.

> [!IMPORTANT]
> If the editor damaged a save or a data file, say so in the title. Restore your files from your own backup, the `.bak` copy next to the file, or *Save list → Save history* — and attach the broken file to the issue if you can.

## Suggesting a feature

Open an issue that starts with **Idea:** and describe what you want to do in the game and why. Screenshots or mock-ups help a lot.

## Translations

The editor is in English for now; more languages are planned. If you want to translate it into your language, open an issue that starts with **Translation:** and name the language.

## Code

The full source code ships with every release: in the editor open **⚙ → Unpack the source code** (or **Download the source code (.zip)**). It contains the pages, JavaScript, styles and PHP, the Windows app in Go, the installer and `HOW TO BUILD.txt`.

1. Build the editor as described in `HOW TO BUILD.txt`.
2. Make your change and test it on a **copy** of your game folder, never on the only one you have.
3. Open an issue describing the change and attach a patch or a link to your fork.

Keep the style of the existing code and texts: short, plain English in the interface.

## License

By contributing you agree that your contribution is released under the project's [CC BY-NC-SA 4.0](LICENSE) license. The editor must stay free — contributions that add payments, ads or paywalls will not be accepted.

## Conduct

Be kind and respectful. See the [Code of Conduct](CODE_OF_CONDUCT.md).
