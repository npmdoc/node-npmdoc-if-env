# api documentation for  [if-env (v1.0.0)](https://github.com/ericclemmons/if-env#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-if-env.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-if-env) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-if-env.svg)](https://travis-ci.org/npmdoc/node-npmdoc-if-env)
#### Simplify npm scripts with "if-env ... && npm run this || npm run that"

[![NPM](https://nodei.co/npm/if-env.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/if-env)

- [https://npmdoc.github.io/node-npmdoc-if-env/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-if-env/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-if-env/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-if-env/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-if-env/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-if-env/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eric Clemmons"
    },
    "bin": {
        "if-env": "bin/if-env.js"
    },
    "bugs": {
        "url": "https://github.com/ericclemmons/if-env/issues"
    },
    "dependencies": {
        "npm-run-all": "1.4.0"
    },
    "description": "Simplify npm scripts with \"if-env ... && npm run this || npm run that\"",
    "devDependencies": {
        "expect": "1.13.4",
        "mocha": "2.3.4"
    },
    "directories": {},
    "dist": {
        "shasum": "6e09082cdd3f2ccfb75baf022a4a971565f6007c",
        "tarball": "https://registry.npmjs.org/if-env/-/if-env-1.0.0.tgz"
    },
    "gitHead": "98fdbf4e651f7cdc88cec9f05d50a47f9768ed03",
    "homepage": "https://github.com/ericclemmons/if-env#readme",
    "keywords": [
        "npm",
        "script",
        "env",
        "if",
        "run"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "ericclemmons"
        }
    ],
    "name": "if-env",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ericclemmons/if-env.git"
    },
    "scripts": {
        "changelog": "npm-run-all changelog:generate changelog:add",
        "changelog:add": "git add CHANGELOG.md",
        "changelog:generate": "github_changelog_generator --future-release $npm_package_version",
        "postversion": "npm-run-all version:amend publish",
        "publish": "npm-run-all publish:git publish:npm",
        "publish:git": "git push && git push --tags",
        "publish:npm": "npm publish",
        "test": "NODE_ENV=test mocha",
        "version": "npm run changelog",
        "version:ammend": "git commit --amend -m \"Release v${npm_package_version}\" && npm run release"
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
