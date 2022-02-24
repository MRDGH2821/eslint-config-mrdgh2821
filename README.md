# eslint-config-mrdgh2821

ESLint config for use in MRDGH2821's projects

v1.1.0 Inspired by [Discord JS ESLint Rules](https://discordjs.guide/preparations/setting-up-a-linter.html#setting-up-eslint-rules)

v2.0 enables all rules of ESLint with few rules having overrides. So if there is any unneeded rule, please modify in the config file. 
## Install

Install using this command.

```sh
npm i eslint-config-mrdgh2821 --save-dev
```

## Usage

To use this config, create an eslint config file and add/edit the following line:

```json
{
  "extends": [
    "eslint-config-mrdgh2821",
    ... //rest of your configs
  ]
}
```

Or follow [this](https://eslint.org/docs/user-guide/configuring/configuration-files#using-a-configuration-from-a-plugin)
