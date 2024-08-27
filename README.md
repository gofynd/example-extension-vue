# Fynd Extension Vue Starter Template
![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)

[![Coverage Status][coveralls-badge]]([coveralls-url])

This repository is the frontend app for Fynd’s extension starter templates. **You probably don’t want to use this repository directly**, but rather through one of the example templates.


## Directory structure
Below is the structure of the project directory along with brief descriptions of the main components:

```
.
├── App.vue                   # The main Vue component
├── README.md                 # Project documentation
├── babel.config.js           # Babel configuration
├── fdk.ext.config.json       # Configuration file for FDK extension
├── index.html                # Main HTML file
├── jest.config.js            # Jest configuration for unit tests
├── main.js                   # Entry point for the Vue application
├── package-lock.json         # Lockfile for npm dependencies
├── package.json              # Project metadata and dependencies
├── pages                     # Page components
│   ├── Home.vue              # Home page component
│   └── NotFound.vue          # 404 Not Found page component
├── public                    # Public assets
├── router.js                 # Vue Router configuration
├── test                      # Test files and configurations
└── vite.config.js            # Vite configuration file contains the configuration for Vite, including server setup and proxy settings.
```

[coveralls-badge]: https://coveralls.io/repos/github/gofynd/example-extension-vue/badge.svg?branch=main&&kill_cache=1
[coveralls-url]: https://coveralls.io/github/gofynd/example-extension-vue?branch=main

