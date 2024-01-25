# Contributing to Meower's Translations

*Please note that this is a work-in-progress.*

## Getting started

You can start collaborating by going to our [Weblate project](https://hosted.weblate.org/engage/meower).

Please **do not** modify the JSON files in the folder, unless if you're trying to [convert the source files into JSON](#converting-into-json).

### Converting into JSON

If you have chosen to translate an project that is a website, then it must be converted into a JSON file. This process will be automated soon™.

```sh
npm install -g po2json
po2json \
  [project folder name]/po/[language code of the language you are translating to].po \
  [project folder name]/json/[language code of the language you are translating to].json \
  -f jed \
  -d [language code of the language you are translating to] \
  --fallback-to-msgid
```

### Example

```sh
po2json \
  Meower-Svelte/po/eo.po \
  Meower-Svelte/json/eo.json \
  -f jed \
  -d eo \
  --fallback-to-msgid
```

