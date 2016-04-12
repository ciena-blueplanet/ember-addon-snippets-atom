# ember-addon-snippets

Ember addon snippets for [Atom](http://atom.io/).

### Adding snippets to your ember addons

1. Create a `snippets` folder at the root of your ember project.
2. Create a `snippets.json` file inside the `snippets` folder.
3. Fill `snippets.json` with snippets. Your file should have the following format.

```json
{
  ".source.hbs": {
    "ember-frost-button": {
      "prefix": "frost-button",
      "body": "{{frost-button}} $1"
    },
    ...
  },
  ".source.js": {
    "Console log": {
      "prefix": "log",
      "body": "console.log $1"
    },
    ...
  },
  ...
}
```

### Using the snippets in Atom

1. Install the package with `apm install ember-addon-snippets` or through the atom preferences panel.
2. Note that there are three ways to trigger the snippets refreshal. I.e, there are three ways to make the package fetch the snippets from your opened project's addons.
  * `ctrl-alt-e`
  * `cd` to your opened project and run `npm install` (Only works if it creates or modifies a `node_modules/ember-*/snippets/snippets.json`  )
  * restart atom


