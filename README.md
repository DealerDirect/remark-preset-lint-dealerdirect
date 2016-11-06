# Dealerdirect: Remark Lint Presets

[![Travis](https://img.shields.io/travis/DealerDirect/remark-preset-lint-dealerdirect.svg?style=flat-square)](https://travis-ci.org/DealerDirect/remark-preset-lint-dealerdirect)
[![npm](https://img.shields.io/npm/v/remark-preset-lint-dealerdirect.svg?style=flat-square)](https://www.npmjs.com/package/remark-preset-lint-dealerdirect)
[![npm](https://img.shields.io/npm/dt/remark-preset-lint-dealerdirect.svg?style=flat-square)](https://www.npmjs.com/package/remark-preset-lint-dealerdirect)
![Maintenance](https://img.shields.io/maintenance/yes/2016.svg?style=flat-square)
![Awesome](https://img.shields.io/badge/awesome%3F-yes-brightgreen.svg?style=flat-square)

> _“Simplicity is prerequisite for reliability.”_ ~ Edsger Dijkstra

Dealerdirect Remark configuration preset for linting Markdown documents.

## Installation

First you'll need to install Remark-cli:

```bash
npm install --save-dev remark-cli
```

Next, install this package.

```bash
npm install --save-dev remark-preset-lint-dealerdirect
```

**Note:** If you are using these tools globally, (using the `-g` flag) then you must also install
`remark-preset-lint-dealerdirect` globally.

Create a `.remarkrc` file in the root of your project. Ensure it at least contains this:

```json
{
  "plugins": {
    "lint": {
      "presets": [
        "remark-preset-lint-dealerdirect"
      ]
    },
  }
}
```

## Usage

Run remark to lint:

```bash
./node_modules/.bin/remark .
```

**Note:** If you are using these tools globally, simply run `remark .`. 

## Contributing

This is an active open-source project. We are always open to people who want to use the code or contribute to it.

We've set up a separate document for our [contribution guidelines].

Thank you for being involved! :heart_eyes:

## Authors & Contributors

The original idea and setup of this repository is by [Franck Nijhof], employee @ Dealerdirect.

For a full list off all author and/or contributors, please check [this page].

## Would you like to work @ Dealerdirect?

Dealerdirect is always on the looking for energetic and hard working developers and devops engineers.

Interested in working at Dealerdirect? Then please be sure to check out [our vacancies].

Did not find a matching vacancy? Just [get in touch]!

[workingatdealerdirect.eu]

## License

The MIT License (MIT)

Copyright (c) 2016 Dealerdirect B.V.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

[contribution guidelines]: CONTRIBUTING.md
[this page]: https://github.com/dealerdirect/remark-preset-lint-dealerdirect/graphs/contributors
[Franck Nijhof]: https://github.com/frenck
[our vacancies]: http://workingatdealerdirect.eu/?post_type=vacancy&s=&department=99
[get in touch]: http://workingatdealerdirect.eu/open-sollicitatie
[workingatdealerdirect.eu]: http://www.workingatdealerdirect.eu
