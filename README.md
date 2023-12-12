# i18n

Translation files for Meower

## Projects

### Meower Svelte

<table>
    <thead>
        <tr>
          <th>Language</th>
          <th>Contributors</th>
          <th>Esolang?</th>
          <th>Percentage Translated</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cat Language</td>
            <td>
                <b><a href="https://github.com/meltland2002">@meltland2002</a></b>   
            </td>
            <td>Yes</td>
            <td>100%</td>
        </tr>
        <tr>
            <td>Esperanto</td>
            <td>
                <b><a href="https://github.com/mdwalters">@mdwalters</a></b>
                <br>
                <b>Edanas</b>
            </td>
            <td>No</td>
            <td><img src="https://hosted.weblate.org/widget/meower/svelte/eo/svg-badge.svg" alt="Translation status"></td>
        </tr>
        <tr>
            <td>French</td>
            <td>
                <b><a href="https://github.com/mdwalters">@mdwalters</a></b>
                <br>
                <b>Edanas</b>
            </td>
            <td>No</td>
            <td><img src="https://hosted.weblate.org/widget/meower/svelte/fr/svg-badge.svg" alt="Translation status"></td>
        </tr>
        <tr>
            <td>Hindi</td>
            <td>
                <b><a href="https://github.com/ajskateboarder">@ajskateboarder</a></b>   
            </td>
            <td>No</td>
            <td><img src="https://hosted.weblate.org/widget/meower/svelte/hi/svg-badge.svg" alt="Translation status"></td>
        </tr>
        <tr>
            <td>Norwegian Bokmål</td>
            <td>
                <b><a href="https://github.com/comradekingu">@comradekingu</a></b>   
            </td>
            <td>No</td>
            <td><img src="https://hosted.weblate.org/widget/meower/svelte/nb_NO/svg-badge.svg" alt="Translation status"></td>
        </tr>
        <tr>
            <td>Spanish</td>
            <td>
                <b><a href="https://github.com/NotFenixio">@NotFenixio</a></b>
                <br>
                <b>Edanas</b>
            </td>
            <td>No</td>
            <td><img src="https://hosted.weblate.org/widget/meower/svelte/es/svg-badge.svg" alt="Translation status"></td>
        </tr>
        <tr>
            <td>Ukrainian</td>
            <td>
                <b><a href="https://github.com/WlodekM">@WlodekM</a></b>
            </td>
            <td>No</td>
            <td><img src="https://hosted.weblate.org/widget/meower/svelte/uk/svg-badge.svg" alt="Translation status"></td>
        </tr>
    </tbody>
</table>

### Meower Website

<table>
    <thead>
        <tr>
          <th>Language</th>
          <th>Contributors</th>
          <th>Esolang?</th>
          <th>Percentage Translated</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Esperanto</td>
            <td>
                <b><a href="https://github.com/mdwalters">@mdwalters</a></b>
            </td>
            <td>No</td>
            <td><img src="https://hosted.weblate.org/widget/meower/website/eo/svg-badge.svg" alt="Translation status"></td>
        </tr>
        <tr>
            <td>Spanish</td>
            <td>
                <b><a href="https://github.com/NotFenixio">@NotFenixio</a></b>
                <br>
                <b>gallegonovato</b>
            </td>
            <td>No</td>
            <td><img src="https://hosted.weblate.org/widget/meower/website/es/svg-badge.svg" alt="Translation status"></td>
        </tr>
    </tbody>
</table>

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
