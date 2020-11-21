# Netlify Build Plugin: Prettier

Enforce prettier code style

> NOTE: [Netlify Build Plugins](https://docs.netlify.com/configure-builds/plugins/?utm_source=github&utm_medium=netlify-plugin-gatsby-cache-jl&utm_campaign=devex) are in beta.

## Usage

To install, add `prettier` and this plugin to your project:

```zsh
yarn add --dev prettier netlify-plugin-prettier
```

or

```zsh
npm install --save-dev prettier netlify-plugin-prettier
```

Then add the following lines to your `netlify.toml` file:

```toml
[[plugins]]
  package = "netlify-plugin-prettier"
```

Note: The `[[plugins]]` line is required for each plugin, even if you have other plugins in your `netlify.toml` file already.

If `prettier` is checking too many things, try adding a `.prettierignore` file.
