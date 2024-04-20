# Directory Tree Generator

<div align="center">
  <a href="https://javascript.info" target="_blank"><img src="https://img.icons8.com/color/452/javascript--v1.png" width="200" alt="JavaScript Logo"></a>
  <h1>Directory Tree Generator</h1>
  <p>The Directory Tree Generator is a tool for visualizing the hierarchical structure of directories and files within a specified directory. It provides scripts and tools for generating directory tree structures.</p>
</div>

<p align="center">
  <a href="https://www.npmjs.com/package/javascript"><img src="https://img.shields.io/npm/dt/javascript" alt="Total NPM Downloads"></a>
  <a href="https://www.npmjs.com/package/javascript"><img src="https://img.shields.io/npm/v/javascript" alt="Latest Stable Version"></a>
  <a href="https://www.npmjs.com/package/javascript"><img src="https://img.shields.io/npm/l/javascript" alt="License"></a>
</p>

## Installation

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/diiaz2910/directory-tree-generator.git
```
Then, navigate to the cloned directory:

```bash
cd directory-tree-generator
```
Make sure you have Node.js installed on your machine. You can download it from [here](https://nodejs.org/).


## Usage

- Get the path of the folder you want to create the tree.
- Paste the path next to `const projectDirectory` in the `script.js` or `script-alternative.js` file and bear in mind to keep double \\.
- To run the project use the following command:

```bash
node script.js
```
or
```bash
node script-alternative.js
```
- `This will print the directory tree structure in your console.`

## Examples

```Tree:
└── .env
└── .gitignore
└── package-lock.json
└── package.json
└── src/
    ├── config/
    │   ├── index.ts
    ├── data/
    ├── graphql/
    │   ├── index.ts
    │   ├── resolvers/
    │   │   ├── resolversInventory.ts
    │   │   ├── resolversPayments.ts
    │   ├── schemas/
    │   │   └── inventory.graphql
    │   │   └── payments.graphql
    ├── index.ts
    ├── mongo/
    │   └── index.ts
└── tsconfig.json
```

- `Or`

```
Tree:
.env/
.gitignore/
package-lock.json/
package.json/
src/
│   config/
│   │   index.ts/
│   data/
│   graphql/
│   │   index.ts/
│   │   resolvers/
│   │   │   resolversInventory.ts/
│   │   │   resolversPayments.ts/
│   │   schemas/
│   │       inventory.graphql/
│   │       payments.graphql/
│   index.ts/
│   mongo/
│       index.ts/
tsconfig.json/
```

## Contribution

If you want to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a branch for your feature: `git checkout -b feature/FeatureName`.
3. Make your changes and commit describing your modifications: `git commit -am 'Add a new feature'`.
4. Push to the branch: `git push origin feature/FeatureName`.
5. Open a pull request on GitHub.

