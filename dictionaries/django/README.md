# CodeTypo Django Dictionary

Django dictionary for codetypo.

This is a pre-built dictionary for use with codetypo.

## Requirements

| Tool                                                                                                                                 | Version |
| ------------------------------------------------------------------------------------------------------------------------------------ | ------- |
| [codetypo](https://github.com/khulnasoft/codetypo)                                                                               | `>= 6`  |
| [Code Spell Checker - Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) | `>= 2`  |

## Installation

Global Install and add to codetypo global settings.

```sh
npm install -g @codetypo/dict-django
codetypo link add @codetypo/dict-django
```

## Uninstall from codetypo

```sh
codetypo link remove @codetypo/dict-django
```

## Manual Installation

The `codetypo-ext.json` file in this package should be added to the import section in your codetypo.json file.

```javascript
{
    // …
    "import": ["@codetypo/dict-django/codetypo-ext.json"],
    // …
}
```

## Updating

This dictionary is generated from django's official documentation index : https://docs.djangoproject.com/en/`VERSION`/genindex/.
To update it, edit `update.py`to match wanted django's `VERSION`, install requirements ([requests](http://docs.python-requests.org) and [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)) and run the script :

```sh
pip install -r requirements.txt
python update.py
```

## Building

Building is only necessary if you want to modify the contents of the dictionary. Note: Building will take a few minutes for large files.

```sh
npm run build
```

## License

WTFPL
