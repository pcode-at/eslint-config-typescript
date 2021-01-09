# @pcode-at/eslint-config-typescript

based on [@seancroach/eslint-config-typescript](https://github.com/seancroach/eslint-config-typescript)

## Highlights

- Enforces all the recommended TypeScript practices
- Ensures your code adheres to the [Prettier Style Guide](https://prettier.io/)
- Lints your import statements to follow the best conventions
- Applies best practices on ESLint directive comments such as
  `/* eslint-disable */`

Like many shared configurations, you _could_ write all the configurations
yourself, but why do that when it's already right here to use!

## Installation

`@pcode-at/eslint-config-typescript` has a few peer dependencies that have to
be downloaded alongside it:

- [`eslint`](https://eslint.org/)
- [`prettier`](https://prettier.io/)
- [`typescript`](https://www.typescriptlang.org/)

Install `@seancroach/eslint-config-typescript` and its peer dependencies through
`npm`:

```
npm install --save-dev @seancroach/eslint-config-typescript eslint prettier typescript
```

## Usage

You can configure ESlint a variety of ways. I suggest to do a majority of your
configurations from your `package.json`:

```json
{
	"name": "my-new-project",
	"eslintConfig": {
		"extends": "@pcode-at/eslint-config-typescript"
	}
}
```

## License

This package is available as open source under the terms of the [MIT License](https://github.com/seancroach/eslint-config-typescript/blob/latest/LICENSE.md).
