<h3 align="center">
    vsc-bundle
</h3>
<h6 align="center">
    <a href="#about">about</a>
    ·
    <a href="#install">install</a>
    ·
    <a href="#dev">contribute</a>
</h6>


### about

- vsc-bundle is a monorepo for 6 extension packs.

    - main
        - all of the extensions given below.

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
🗀 vsc-bundle
├── 🗀 main
│   ├── 🖹 LICENSE
│   ├── 🗎 package.json
│   └── ▼ README.md
│   └── 🗋 .vscodeignore
├── 🗀 nodejs
│   ├── 🖹 LICENSE
│   ├── 🗎 package.json
│   └── ▼ README.md
│   └── 🗋 .vscodeignore
├── 🗀 python
│   ├── 🖹 LICENSE
│   ├── 🗎 package.json
│   └── ▼ README.md
│   └── 🗋 .vscodeignore
├── ▼ README.md
├── 🗀 rust
│   ├── 🖹 LICENSE
│   ├── 🗎 package.json
│   └── ▼ README.md
│   └── 🗋 .vscodeignore
├── 🗀 svelte
│   ├── 🖹 LICENSE
│   ├── 🗎 package.json
│   └── ▼ README.md
│   └── 🗋 .vscodeignore
└── 🗀 vscode
    ├── 🖹 LICENSE
    ├── 🗎 package.json
    └── ▼ README.md
    └── 🗋 .vscodeignore
```