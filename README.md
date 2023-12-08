# i18n

Translation files for Meower

## Projects

Languages marked with **[EL]** means that it is an esolang (esoteric language, or a easter egg language).

### Meower Svelte

#### Cat Language [EL]

Maintained by **[@meltland2002](https://github.com/meltland2002)**

#### Esperanto

Maintained by **[@mdwalters](https://github.com/mdwalters)**

#### French

Maintained by **[@mdwalters](https://github.com/mdwalters)**

#### Hindi

Maintained by **[@ajskateboarder](https://github.com/ajskateboarder)**

#### Norwegian Bokmål

Maintained by **[@comradekingu](https://github.com/comradekingu)**

#### Spanish

Maintained by **[@NotFenixio](https://github.com/NotFenixio)**

#### Ukrainian

Maintained by **[@WlodekM](https://github.com/WlodekM)**

### Meower Website

#### Esperanto

Maintained by **[@mdwalters](https://github.com/mdwalters)**

#### Norwegian Bokmål

Maintained by **[@comradekingu](https://github.com/comradekingu)**

#### Spanish

Maintained by **[@NotFenixio](https://github.com/NotFenixio)**

## Contributing translations

You can start collaborating by clicking the image above to go to our Weblate project.

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

## Stats

### Meower Svelte

![Status of the Meower Svelte translations](https://hosted.weblate.org/widget/meower/svelte/multi-auto.svg)

### Meower Website

![Status of the Meower Website translations](https://hosted.weblate.org/widget/meower/website/multi-auto.svg)
