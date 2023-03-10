<h3 align="center">
    vsc-bundle
</h3>
<h6 align="center">
    <a href="#about">about</a>
    ยท
    <a href="#install">install</a>
    ยท
    <a href="#dev">contribute</a>
</h6>
<div align="center">

![GitHub](https://img.shields.io/github/license/1yib/vsc-bundle?color=A3BE8C&style=flat-square)
![Installs](https://vsmarketplacebadges.dev/installs-short/1YIB.main-bundle.svg?&logo=visualstudiocode&color=A3BE8C)
![Version](https://vsmarketplacebadges.dev/version-short/1YiB.main-bundle.svg?&logo=visualstudiocode&color=A3BE8C&label=version)

</div>

### about

- vsc-bundle is a monorepo for 6 extension packs.

    - main
        - extension pack of all the extensions given below.

    - rust
        - extensions for [`rust-lang`](https://rust-lang.org)
    - nodejs
        - extension for [`js`](https://nodejs.org/en ) / [`ts`](https://www.typescriptlang.org/)
    - svelte
        - extensions for [`svelte`](https://svelte.dev)
    - python
        - extensions for [`python`](https://www.python.org)
    - vscode
        - extensions for general purpose use on [`vscode`](vscode:)

<br />


### install

1. press: <kbd>Ctrl + P</kbd>

2. type `ext install 1YiB.main-bundle`

3. press <kbd>Enter</kbd>

### contribute

- suggest extensions to add in the form of issues

- create pull request for adding extensions

- file-structure

```
๐ vsc-bundle
โโโ ๐ main
โ   โโโ ๐ assets
โ   โ   โโโ ๐ป icon.png
โ   โโโ ๐น LICENSE
โ   โโโ ๐ package.json
โ   โโโ โผ README.md
โ   โโโ ๐ .vscodeignore
โโโ ๐ nodejs
โ   โโโ ๐ assets
โ   โ   โโโ ๐ป icon.png
โ   โโโ ๐น LICENSE
โ   โโโ ๐ package.json
โ   โโโ โผ README.md
โ   โโโ ๐ .vscodeignore
โโโ ๐ python
โ   โโโ ๐ assets
โ   โ   โโโ ๐ป icon.png
โ   โโโ ๐น LICENSE
โ   โโโ ๐ package.json
โ   โโโ โผ README.md
โ   โโโ ๐ .vscodeignore
โโโ โผ README.md
โโโ ๐ rust
โ   โโโ ๐ assets
โ   โ   โโโ ๐ป icon.png
โ   โโโ ๐น LICENSE
โ   โโโ ๐ package.json
โ   โโโ โผ README.md
โ   โโโ ๐ .vscodeignore
โโโ ๐ svelte
โ   โโโ ๐ assets
โ   โ   โโโ ๐ป icon.png
โ   โโโ ๐น LICENSE
โ   โโโ ๐ package.json
โ   โโโ โผ README.md
โ   โโโ ๐ .vscodeignore
โโโ ๐ vscode
โ   โโโ ๐ assets
โ   โ   โโโ ๐ป icon.png
    โโโ ๐น LICENSE
    โโโ ๐ package.json
    โโโ โผ README.md
    โโโ ๐ .vscodeignore
```