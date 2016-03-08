# md-date-time-picker

[![Dependency Status](https://david-dm.org/puranjayjain/md-date-time-picker.svg)](https://david-dm.org/puranjayjain/md-date-time-picker)

> An implementation of [Material Design Picker](https://www.google.com/design/spec/components/pickers.html)
components in vanilla CSS, JS, and HTML

## Browser Support

Supported evergreen browsers:

- Chrome
- Edge
- Firefox
- Opera

Supported versioned browsers:

- Internet Explorer 8
- Safari 8
- Mobile Safari 8

## Dependency

### Moment
Why? because parsing dates correctly is not every browser's cup of :tea: and also according to [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) standard and also timezones are one more thing that are required by a lot of users.

ok. Not satisfied with the answer?

Let's take an example:

```js
  new Date('1/10/2016')
```

What should it output? ... well it is interpreted as 1st October 2016 in some browsers and 10th January 2016 in some.

### What's included

In the repo you'll find the following directories and files.

| File/Folder     | Provides                                       |
|-----------------|------------------------------------------------|
| CONTRIBUTING.md | contribution guidelines.                       |
| gulpfile.js     | gulp configuration.                            |
| LICENSE         | Project license information.                   |
| package.json    | npm package information.                       |
| README.md       | Details for quickly understanding the project. |
| src             | Source code.                                   |
| dist            | Distributable code.                            |
| test            | Project test files.                            |

### Build

To get started modifying the components or the docs, first install the necessary
dependencies, from the root of the project:

```bash
npm install
```

```bash
gulp default
```

Most changes made to files inside the `src` or the `docs` directory will cause
the page to reload. This page can also be loaded up on physical devices thanks
to BrowserSync.

> MDL requires NodeJS 0.12.

## Versioning

For transparency into our release cycle and in striving to maintain backward
compatibility, Material Design Lite is maintained under
[the Semantic Versioning guidelines](http://semver.org/). Sometimes we screw up,
but we'll adhere to those rules whenever possible.

## License

© Puranjay Jain, 2016. Licensed under an
[MIT License](https://github.com/puranjayjain/md-date-time-picker/blob/master/LICENSE.md)
license.
