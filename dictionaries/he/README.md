# CodeTypo he Dictionary

Dictionary for Hebrew language

This is a pre-built dictionary for use with codetypo.

# About the Dictionary

The Hebrew Dictionary has been compiled from the Hunspell Hebrew Dictionary:

> By the Hspell project (http://hspell.ivrix.org.il/).
> Hspell version 1.4 was used.
> Copyright 2004-2017, Nadav Har'El and Dan Kenigsberg
> The dictionary (this file and the corresponding word list)
> is licensed under the GNU Affero General Public License

But, due to the complexity of the Hebrew language, a significant portion of the dictionary was not able to be
included in this extension.

<!--- codetypo:ignore hspell, Nadav Har'El, Dan Kenigsberg --->

## Installation

Global Install and add to codetypo global settings.

```sh
npm install -g @codetypo/dict-he
codetypo link add @codetypo/dict-he
```

## Uninstall from codetypo

```sh
codetypo link remove @codetypo/dict-he
```

## Manual Installation

The `codetypo-ext.json` file in this package should be added to the import section in your codetypo.json file.

```javascript
{
    // …
    "import": ["@codetypo/dict-he/codetypo-ext.json"],
    // …
}
```

## Building

Building is only necessary if you want to modify the contents of the dictionary. Note: Building will take a few minutes for large files.

```sh
npm run build
```

## License

AGPLv3

> Some packages may have other licenses included.
