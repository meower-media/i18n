# i18n

Translation files for Meower

## Projects

Languages marked with **[EL]** means that it is an esolang (esoteric language, or a easter egg language).

### Meower Svelte

#### Cat Language [EL]

Maintained by **[@meltland2002](https://github.com/meltland2002)**

#### Esperanto

Maintained by **[@mdwalters](https://github.com/mdwalters)**

### Meower Website

Currently has no maintainers maintaining translations.

## Contributing translations

This repo is not managed by any internationalization website, so you must manually edit the `po`/`pot` files by hand. Please **do not** modify the JSON files in the folder, unless if you're trying to [convert the source files into JSON](#converting-into-json).

### Converting into JSON

If you have chosen to translate an project that is a website, then it must be converted into a JSON file. This process will be automated soon™.

```sh
npm install -g po2json
po2json \
  [project folder name]/[language code of the language you are translating to].po \
  [project folder name]/[language code of the language you are translating to].json \
  -f jed \
  -d [language code of the language you are translating to] \
  --fallback-to-msgid
```
