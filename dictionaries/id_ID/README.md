# CodeTypo Indonesia Dictionary

Indonesia dictionary for codetypo.

This is a pre-built dictionary for use with CodeTypo.

## Installation

Global Install and add to CodeTypo global settings.

```sh
npm install -g @codetypo/dict-id
codetypo link add @codetypo/dict-id
```

## Uninstall from CodeTypo

```sh
codetypo link remove @codetypo/dict-id
```

## Manual Installation

Manual installation is useful if you want to include this dictionary as part of your CI/CD lint process.

```
npm i @codetypo/dict-id
```

The `codetypo-ext.json` file in this package should be added to the import section in your `codetypo.json` file.

```javascript
{
    // …
    "import": ["@codetypo/dict-id/codetypo-ext.json"],
    // …
}
```

# Dictionary Development

See: [How to Create a New Dictionary](https://github.com/khulnasoft/codetypo-dicts#how-to-create-a-new-dictionary)

## Source

[Indonesia hunspell dictionary. Kamus Bahasa Indonesia untuk program hunspell.](https://github.com/shuLhan/hunspell-id)

## License

LGPL-3.0

> Some packages may have other licenses included.

<!--- @@inject: ../../static/footer.md --->

<br/>

---

<p align="center">
Brought to you by <a href="https://streetsidesoftware.com" title="Street Side Software">
<img width="16" alt="Street Side Software Logo" src="https://i.imgur.com/CyduuVY.png" /> Street Side Software
</a>
</p>

<!--- @@inject-end: ../../static/footer.md --->
