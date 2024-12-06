# turmag-stylelint-config

Turmag's reusable stylelint-config

# Languages
#### Web #
* [Scss](https://sass-lang.com): [stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard) + [stylelint-config-recommended](https://github.com/stylelint/stylelint-config-recommended) + [stylelint-config-recommended-scss](https://github.com/stylelint-scss/stylelint-config-recommended-scss) + [stylelint-config-recommended-vue](https://github.com/ota-meshi/stylelint-config-recommended-vue)
* [Vue](https://vuejs.org): [stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard) + [stylelint-config-recommended](https://github.com/stylelint/stylelint-config-recommended) + [stylelint-config-recommended-scss](https://github.com/stylelint-scss/stylelint-config-recommended-scss) + [stylelint-config-recommended-vue](https://github.com/ota-meshi/stylelint-config-recommended-vue) + [postcss-html](https://github.com/ota-meshi/postcss-html)

# Features
**Zero-Dependency**<br>
No need to install 5 plugins and 2 parsers: each language's latest plugin is bundled and configured.

**Zero-Config**<br>
No need to remember each plugin's parserOptions;

# Installation
1. You'll first need to install [Stylelint](https://stylelint.io):
```
npm i stylelint@^16.11 --save-dev

# Or run this to use yarn
yarn add stylelint@^16.11 --dev

# Or run this to use pnpm
pnpm add stylelint@^16.11 --save-dev
```

2. Install [turmag-stylelint-config](https://www.npmjs.com/package/turmag-stylelint-config).

```
npm i turmag-stylelint-config --save-dev

# Or run this to use yarn
yarn add turmag-stylelint-config --dev

# Or run this to use pnpm
pnpm add turmag-stylelint-config --save-dev
```

3. Create `stylelint.config.js` in your project root.

# Usage
In `stylelint.config.js`:
* Import config from turmag-stylelint-config

```
import config from 'turmag-stylelint-config';
```
* Use this config with your optional rules:

```
export default {
    extends: ['turmag-stylelint-config'],

    // Your rules there
    {
        rules: {
            ...
        },
    },
};
```

# License
This code is licensed under the [MIT](https://github.com/Turmag/turmag-stylelint-config/blob/main/LICENSE) License.