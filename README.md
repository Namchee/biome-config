# @namchee/biome-config

Shareable configuration BiomeJS config for personal use. Definitely opinionated and under development.

## Installation

```bash
# Using npm
npm install -D @namchee/biome-config

# Using yarn
yarn add -D @namchee/biome-config

# Using pnpm
pnpm install -D @namchee/biome-config

# Using bun
bun install -D @namchee/biome-config
```

## Usage

You can extend your BiomeJS config using `extends` keyword.

```jsonc
{
    "$schema": "https://biomejs.dev/schemas/1.7.0/schema.json",
    "extends": ["@namchee/biome-config/biome.json"]
}
```

## Compatibility

- **Use for**: JavaScript, TypeScript, React.
- **Do not use for**: HTML superlanguage projects such as Vue, Svelte, and Astro. Use [`@namchee/eslint-config`](https://github.com/Namchee/eslint-config-namchee) instead.

> [!IMPORTANT]
> Biome currently only support frontmatters and script tags when parsing HTML superlanguage files, which makes it possible to cause false alarm.

## License

This project is licensed under the [MIT License](./LICENSE)
