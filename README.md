# ember-addon-snippets-atom

Ember addon snippets for [Atom](http://atom.io/).

### Consuming ember addon snippets in Atom

1. Install the package with `apm install ember-addon-snippets` or through the atom preferences panel.
2. Note that there are 4 ways to trigger the snippets refreshal. I.e, to make the package fetch the snippets from your opened project's addons.
  * restart atom
  * add or remove a project folder
  * press `ctrl-alt-e`
  * `cd` to your opened project and run `npm install` (Only works if it creates or modifies a `node_modules/ember-*/snippets/snippets.json`)

Follow these [instructions](https://github.com/ciena-blueplanet/ember-addon-snippets/blob/master/README.md#adding-snippets-to-your-ember-addons) to add snippets compatible with this package to your ember addons. 
