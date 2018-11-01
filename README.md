# sasslint-config

[![INC](https://img.shields.io/badge/%F0%9F%92%A1-IdeasNeverCease/sasslint--config-51dcfb.svg?style=flat-square)](https://git.inc.sh/IdeasNeverCease/sasslint-config)

> Recommended Sass Lint settings for !NC projects



### Installation
```bash
$ npm i @inc/sasslint-config -D
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
