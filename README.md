
# Install

```base
$ npm install react-app-rewire-sass-modules --save-dev
```

# Add it to your project

- [Rewire your app][1] than modify config-overrides.js

[1]: https://github.com/timarney/react-app-rewired#how-to-rewire-your-create-react-app-project

```base
const rewireSass = require('react-app-rewire-sass-modules');

module.exports = function override(config, env) {

  config = rewireSass(config, env);

  return config;

}
```
