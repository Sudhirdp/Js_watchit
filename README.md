# Watchit - Node.js Code Watcher

Watchit is a simple Node.js practice project that enables you to track changes in your Node.js JavaScript files. It's designed to automatically restart your Node.js application whenever changes are detected in the specified file. It also restarts the program when files are deleted.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Acknowledgments](#acknowledgments)

## Introduction

`watchit` is a command-line tool developed as part of the Udemy JavaScript course. It serves a similar purpose to `nodemon`, providing an easy way to monitor file changes and streamline the development process.

## Usage

To use `watchit`, follow these steps:

1. Install the required npm packages:

    ```bash
    npm install caporal chokidar lodash.debounce chalk
    ```

2. Clone the repository and install the project dependencies:

    ```bash
    git clone https://github.com/your-username/watchit.git
    cd watchit
    npm install
    ```

3. Run `watchit` with the following command:

    ```bash
    node watchit.js [filename]
    ```

    Replace `[filename]` with the name of the file you want to monitor. If no filename is provided, the default is set to `index.js`.

## Prerequisites

Before using `watchit`, make sure you have the following npm packages installed:

- [caporal](https://www.npmjs.com/package/caporal)
- [chokidar](https://www.npmjs.com/package/chokidar)
- [lodash.debounce](https://www.npmjs.com/package/lodash.debounce)
- [chalk](https://www.npmjs.com/package/chalk)

Ensure that the `fs` and `child_process` modules from the Node.js API are also required in your project.

## Installation

Clone the repository and install the required npm packages:

```bash
git clone https://github.com/your-username/watchit.git
cd watchit
npm install

***

```shell
# By default it will search for index.js
watchit
# Optionally pass in a filename/path to watch
watchit test.js
```
