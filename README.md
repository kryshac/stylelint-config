# @starlab/stylelint-config

StarLab StyleLint extensible and sharable configuration.

## Usage

Install the configuration as a npm package:

```sh
$ npm install --save-dev @starlab/stylelint-config

# --- OR ---

$ yarn add --dev @starlab/stylelint-config
```

and then add it as extension in your `.stylelintrc.json` file:

```json
{
  "extends": ["@starlab/stylelint-config"]
}
```

The corresponding `.stylelintrc.yaml` file looks like this:

```json
extends:
  - @starlab/stylelint-config
```
