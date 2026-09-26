# Security policy

## Get the editor only from here

The only official source of the **Jagged Alliance 2 Game Editor** is the [Releases](../../releases) page of this repository.

- Before running `JA2-Game-Editor.exe`, compare its **SHA-256** checksum with the one in the release notes (see [Verify the download](README.md#verify-the-download-sha-256)) and scan it with an online multi-engine scanner.
- The editor is **free**. If someone sold it to you, asked you to pay for it or sent it through another site, treat that copy as unsafe and delete it.

## Supported versions

Only the [latest release](../../releases/latest) gets fixes. The editor offers new releases itself (**⚙ → Check for updates**); please update before reporting a problem.

## Reporting a vulnerability

Please report security problems **privately**, not in a public issue:

- a flaw in the editor that could harm a user's computer or files (e.g. through a crafted save, map, mod archive or update);
- a fake or modified copy of the editor being spread somewhere.

Use **Security → Report a vulnerability** in this repository. If that button is not available, open an [issue](../../issues) titled **Security: contact request** without any details, and the maintainer will contact you.

Include what is affected, how to reproduce it and the editor version. You will get an answer as soon as possible; fixed problems are credited in the release notes unless you prefer to stay anonymous.

## Your game files

The editor writes directly to your saves and game data, and it can damage them. This is not a vulnerability, but please **always keep your own backup** of the game folder and saves.
