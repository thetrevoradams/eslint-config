# eslint-config

* A common ESLint configuration for Teton Dev. The base is airbnb's config (a highly used and tested configuration).

Available at [https://www.npmjs.com/package/@tetondev/eslint-config](https://www.npmjs.com/package/@tetondev/eslint-config)

## Usage

Install the package (along with `eslint` - required peer-dependency) to your project's dev dependencies:

```
npm i -D @tetondev/eslint-config eslint
```

In your project's `package.json` add the following

```
"eslintConfig": {
    "extends": [
      "@tetondev/eslint-config"
    ]
  }
```

## Optional config

It can be helpful to adjust the format settings in your code editor. In VS Code the option to `formatOnSave` can be enabled to auto-correct linting issues.