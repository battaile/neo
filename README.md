# Neo

Scaffold out a React-based front-end application with initial zero configuration

## Features

- React, Redux, React Router
- Webpack
- ESLint, Babel, ES2015 + modules, Stage 0 preset
- Tests and coverage with Karma, Mocha, Chai, and Enzyme
- Node.js v6
- Bootstrap 4 and Sass
- Travis CI
- Immutable

## Sample App

To view a sample application which contains the initial output of Neo after
running `init`, check out [eliperelman/neo-example](https://github.com/eliperelman/neo-example).

## Initialize empty project

#### Global

```bash
npm install -g mozilla-neo
mkdir <project-name> && cd <project-name>
neo init # and follow the prompts
```

#### Local

```bash
mkdir -p <project-name>/node_modules && cd <project-name>
npm install mozilla-neo
node_modules/.bin/neo init # and follow the prompts
```

##### Sample output

```bash
→ create package.json
→ create src/
→ create tests/
→ create .gitignore
→ create .travis.yml
→ create LICENSE
→ create README.md
```

## Install in existing project

```bash
npm install --save mozilla-neo
```

Make changes to configuration by following the [scaffold init guide](https://github.com/mozilla/neo/tree/master/commands/init/templates#configuration).

## Workflow

- Add code to `src/` and tests to `tests/`.
- Build and watch changes in `src/` with `npm start`.
- Lint and build the project with `npm run build`.
- Run tests with `npm test`.

## Contribute

- Issue Tracker: [https://github.com/mozilla/neo/issues](https://github.com/mozilla/neo/issues)
- Source Code: [https://github.com/mozilla/neo](https://github.com/mozilla/neo)
- Code of Conduct: [Adapted from Rust CoC](https://www.rust-lang.org/conduct.html)

Note: There is currently a [bug in npm](https://github.com/npm/npm/issues/13385) from being able to run the `npm test`
command in this repo in development. As a workaround, make sure you are using a npm 3.8.9 or less.

## Support

If you are having issues, please let us know.
We have an IRC channel `#tc-frontend` on [Mozilla IRC](https://wiki.mozilla.org/IRC)


## License

This project is licensed under the [Mozilla Public License v2.0](https://github.com/mozilla/neo/blob/master/LICENSE)
