# css-language-server

Language server for CSS, LESS, and SASS. Extracted from [VSCode](https://github.com/Microsoft/vscode/tree/master/extensions/css) and made reusable.

## Why?

This is an implementation of the [language server protocol](https://github.com/Microsoft/language-server-protocol/blob/master/protocol.md), which makes completion, hover info, go-to definition, etc. available across editors.

## Features

- [x] CSS Support
- [x] LESS Support
- [x] SASS Support
- [ ] Validation
- [x] Definition provider
- [x] Hover provider
- [x] References provider
- [x] Completion provider

## Installation

```
npm install -g css-language-server
```

This language server has been tested primarily with [Oni](https://www.onivim.io/), and it is forked from [VSCode](https://github.com/Microsoft/vscode), but should work with any client that allows for configurable language servers.

Feel free to contribute and add setup steps for your favorite editor.

## Launching the Server

The server can be launched with one of the following transports:
```
css-language-server --stdio
css-language-server --socket={number}
css-language-server --node-ipc
```

## Contributing

PRs are welcome. Clone the repo and run:
```
npm install
npm run build
```

## License

This project is licensed under the [MIT License](LICENSE.md)

This is a derived work - please see [Third Party Notices](ThirdPartyNotices.txt) for the original copyright and license.
