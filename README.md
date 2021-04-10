# @devsht/prettier-config

Reusable prettier config

## Installation

```bash
npm i -D @devsht/prettier-config
```

or

```
yarn add --dev @devsht/prettier-config
```

## Usage

Add a key in your **package.json** file.

```
"prettier": "@devsht/prettier-config"
```

**OR**

Create a **.prettierrc** , **.prettierrc.yaml** , **.prettierrc.yml** or **.prettierrc.json** file and export a string.

```
"@devsht/prettier-config"
```

**OR**

Create a **prettier.config.js** or **.prettierrc.js** file and export an object.

```
module.exports = {
  ...require("@devsht/prettier-config"),
  tabWidth: 2,
};
```
