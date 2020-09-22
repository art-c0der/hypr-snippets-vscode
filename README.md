# [Hypr Syntax Snippets](https://marketplace.visualstudio.com/items?itemName=temu4.hypr-snippets)

Hypr syntax snippets for Visual Studio Code.

## Screenshot

![Screenshot](https://github.com/Temu4/hypr-snippets/raw/master/images/screenshot.gif)

## User Settings

For better syntax hightlights you can define `.hypr` and `.hypr.live` files as `.php`.

Open `Preferences` -> `Settings`

```json
    "files.associations": {
      "*.hypr": "php",
      "*.hypr.live": "php"
    }
```

## Features

* Hypr snippets

## Hypr Snippets:

| Trigger               | Snippet                                    |
|-----------------------|--------------------------------------------|
| hypr: block           | {% block ... %}...{% endblock ... %}       |
| hypr: block+parent    | {% block ... %}{% parent %}...{% endblock ... %}       |
| hypr: comment         | {% comment %}...{% endcomment %}           |
| hypr: dropzone        | {% dropzone ... %}                         |
| hypr: filter          | {{ value&#124;filter }}                         |
| hypr: for             | {% for %}...{% endfor %}                   |
| hypr: for+reverse     | {% for reversed %}...{% endfor %}          |
| hypr: if              | {% if %}...{% endif %}                     |
| hypr: if-else         | {% if %}...{% else %}...{% endif %}        |
| hypr: include         | {% include ... %}                          |
| hypr: include+options | {% include ... with ... %}                 |
| hypr: label           | {{ labels...} }}                           |
| hypr: make+image      | {% make_url 'image' ... with ... %}        |
| hypr: make+product    | {% make_url 'product' ... with ... %}      |
| hypr: make+category   | {% make_url 'category' ... %}              |
| hypr: make+facet      | {% make_url 'facet' ... %}                 |
| hypr: make+sorting    | {% make_url 'sorting' ... %}               |
| hypr: make+cdn        | {% make_url 'cdn' ... %}                   |
| hypr: make+paging     | {% make_url 'paging' ... with ... %}       |
| hypr: make+stylesheet | {% make_url 'stylesheet' ... %}            |
| hypr: make+stylesheet | {% make_url 'stylesheet' ... %}            |
| hypr: preload_json    | {% preload_json ... %}                     |
| hypr: require_script  | {% require_script ... %}                   |
| hypr: set_var         | {% set_var ... %}                          |
| hypr: set             | {% set ... %}                              |
| hypr: with            | {% with %}...{% endwith %}                 |

## Contact

Please apply any [issues](https://github.com/Temu4/hypr-snippets/issues) or have a suggestion please touch me in Linkedin [Artem Vorobiov](https://www.linkedin.com/in/artem-vorobiov/).

## Release Notes 

### 0.1.1

- Update README. 

### 0.1.0

- Add basic snippets. 
- Add description of the extension in README.

Please open [Changelog](https://github.com/Temu4/hypr-snippets/blob/master/CHANGELOG.md) for more information.

## License

Please read [License](https://github.com/Temu4/hypr-snippets/blob/master/LICENSE.md) for more information.
