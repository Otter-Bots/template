# TypeScript Sapphire Bot Template

This is a basic setup of a Discord bot using the [Sapphire Framework][sapphire], written in TypeScript.

## How do I use it?

### Prerequisite

```sh
npm install
```

### Development

This example can be run with `tsc-watch` to watch the files and automatically restart your bot.

```sh
npm run watch:start
```

### Production

You can also run the bot with `npm dev`, this will first build your code and then run `node ./dist/index.js`. But this is not the recommended way to run a bot in production.

## License

Dedicated to the public domain via the [Unlicense], courtesy of the Sapphire Community and it's contributors.

[Sapphire]: https://github.com/sapphiredev/framework
[Unlicense]: https://github.com/sapphiredev/examples/blob/main/LICENSE.md
