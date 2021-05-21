# ⚛️ eslint-config-kunalnagarco

![CircleCI](https://img.shields.io/circleci/build/github/kunalnagarco/javascript/master?token=6961e38f0ab710cad0cbba48bf771ee3bdb2e225) [![npm](https://img.shields.io/npm/v/@kunalnagarco/eslint-config?color=blue)](https://www.npmjs.com/package/@kunalnagarco/eslint-config)

An ESLint shareable config that extends `eslint-config-airbnb` with a few custom options.

## 🛠 Install

### Step 1

Add the package to your `devDependencies`:

```
$ npm install eslint-config-kunalnagarco --save-dev
```

### Step 2

Install the `peerDependencies` using:

```
npx install-peerdeps eslint-config-kunalnagarco --dev
```

## 💻 Usage

Add it to the `extends` section of your `.eslintrc` configuration file.

```json
{
  "extends": ["kunalnagarco"]
}
```

## 💼 Optional

If you want you can configure/override rules as well:

```json
{
  .
  ...
  ....
  "overrides": {
    "override-rule-name": "override-rule-option"
  },
  "rules": {
    "rule-name": "rule-option"
  }
}
```

## 👨‍💻 Support

Please create a new issue [here](https://github.com/kunalnagarco/javascript/issues)
