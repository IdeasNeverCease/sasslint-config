# sasslint-config

[![INC](https://img.shields.io/badge/%E2%9C%A8-IdeasNeverCease/sasslint--config-51dcfb.svg?style=flat-square)](https://code.webb.page/IdeasNeverCease/sasslint-config)

> Recommended Sass Lint settings for !NC projects

# DEPRECATED

[Sass Lint](https://github.com/sasstools/sass-lint) has not been maintained for two years at this time of writing. Therefore, this module has been deprecated in favor of [this !NC stylelint config](https://code.webb.page/IdeasNeverCease/stylelint-config).



### Installation
```bash
$ npm i sass-lint @inc/sasslint-config -D
```



### Usage

> Sass Lint [configuration](https://github.com/sasstools/sass-lint#configuring)

##### YAML config

```yaml
options:
  config-file: ./node_modules/@inc/sasslint-config/config.json
```

##### JSON config

```json
options: {
  "config-file": "./node_modules/@inc/sasslint-config/config.json"
}
```

##### Command line config

```bash
sass-lint --config ./node_modules/@inc/sasslint-config/config.json --verbose --no-exit
```

##### package.json config

```json
{
  "name": "your_project",
  "scripts": {
    ...,
    "test:sass": "sass-lint --config ./node_modules/@inc/sasslint-config/config.json --verbose --no-exit",
    ...
  }
}
```

If your script was called `test:sass` you could then run `npm run test:sass` and your Sass files would be linted.



### License

[BSD-3-Clause](LICENSE) Copyright © 2018-19, Ideas Never Cease
