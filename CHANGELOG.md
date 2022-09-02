## 1.2.1 - 02 Sep 2022

#### Fixed
- Fix bugs on Microsoft Windows
- Fix issue that prevented opening Copilot digest in some cases

## 1.2.0 - 02 Sep 2022
### Added
- Tracking of GitHub Copilot events
- Add GitHub Copilot Digest
- Add extension info in event data

### Fixes
- Fix minor issue with navigation events calculation
- Fix minor issue related to event timestamps

## 1.1.0 - 18 Mar 2022
### Added 
- Support for `Java` language features by instrumenting the  `redhat.java` extension;
- Support for `Python` language features by instrumenting the `ms-python.python` extension;
- Support for `html`, `php`, `css`, `markdown`, `json` language features;
- Support for new language feature / language server events: call hierarchies, linked editing ranges, and semantic tokens. 
- Basic support for command execution tracking for all supported extensions. 

### Fixes
- Fixed event JSON serialization, omitting circular references in serialized objects.


## 1.0.0 - 06 Jun 2021
### Initial Release
* Support for interaction data from extensions using [Language Server Protocol][lsp] (e.g., `Scala` through [Metals][metals]) 
* Support for interaction data coming from [vscode language features][vsclf] for the following language and extension pairs:
  * `TypeScript` and `JavaScript` from `vscode.typescript-language-features` integrated extension.
* Session exploration and basic analytics through a Session Digest.

[lsp]: https://microsoft.github.io/language-server-protocol/
[metals]: https://scalameta.org/metals/
[vsclf]: https://code.visualstudio.com/api/language-extensions/overview
