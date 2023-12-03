# i18n

Translation files for Meower

## Projects

Languages marked with **[EL]** means that it is an esolang (esoteric language, or a easter egg language).

### Meower Svelte

#### Cat Language [EL]

Maintained by **[@meltland2002](https://github.com/meltland2002)**

#### Spanish

Maintained by **[@NotFenixio](https://github.com/NotFenixio)**

### Meower Website

Currently has no maintainers maintaining translations.

## Contributing translations

<a href="https://hosted.weblate.org/engage/meower/">
<img src="https://hosted.weblate.org/widget/meower/svelte/multi-auto.svg" alt="Status of translations. Click to collaborate!" />
</a>

You can start collaborating by clicking the image above. 

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
