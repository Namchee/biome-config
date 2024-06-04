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
    "extends": ["./node_modules/@namchee/biome-config/biome.json"]
}

```

> [!NOTE]
> Since BiomeJS API might change in the future, how the configuration is extended might also be changed in the future.


## License

This project is licensed under the [MIT License](./LICENSE)
