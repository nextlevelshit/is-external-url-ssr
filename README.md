<div align="center">
  <h1>isExternal()</h1>
  <sup>URL · Utility · external · internal · a · href</sup>
</div>

## Quick start

1.  **Installation**

    Use npm/yarn CLI to install the repository.

    ```shell
    yarn add is-url-external-ssr

    # OR

    npm install is-url-external-ssr
    ```

2. **Usage**

    ## Usage
    ```javascript
    const isExternal  from "is-url-external-ssr"

    console.log(
      isExternal('https://github.com/mrded/is-url-external')
        ? "It's an external link"
        : "It's an internal link width the same hostname"
    )
    ```

## What's inside?

A quick look at the top-level files and directories you'll see in a Gatsby project.

    .
    ├── /node_modules
    ├── index.js
    ├── LICENSE
    ├── package.json
    ├── README.md
    └── yarn.lock

1.  **`/node_modules`**: This directory contains all of the modules of code that your project depends on (npm packages) are automatically installed.

2.  **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

3.  **`index.js`**: Main piece of code and functionality.

4.  **`LICENSE`**: License agreement for usage and modification of this software.

5. **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

6. **`README.md`**: A text file containing useful reference information about our project.

7. **`yarn.lock`** (See `package.json` above, first). This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. **(You won’t and shouldn't change this file manually).**

## Who to ask?

This repository is maintained by [Michael Czechowski](mailto:mail@dailysh.it) in 2020. If you're having any questions, don't hesitate to write an email.

## Contributions

This software is based on [Dmitry Demenchuk](https://github.com/mrded)'s software [`is-url-external`](https://github.com/mrded/is-url-external). Thanks to him!