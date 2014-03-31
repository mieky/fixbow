# fixbow

A `bower.json` file scrubber.

Based on [fixpack](https://github.com/HenrikJoreteg/fixpack), a package.json file scrubber for the truly insane by Henrik Joreteg.

It will re-write your [bower.json](https://github.com/bower/bower.json-spec) file as follows:

- name first
- description second
- version third
- authors fourth
- all other keys in alphabetical order
- dependencies and devDependencies sorted alphabetically
- append operating system appropriate newline at the end of the file

It will warn you if any of these are missing:

- authors
- repository
- keywords
- main
- ignore
- homepage
- license

Fix all indenting to 2 spaces.

## Usage

1. Install it globally

```
npm install -g fixbow
```

2. Run it in the same directory as your bower.json, that's it.

```
fixbow
```

## Changelog

- 0.0.1 - Initial release

## Credits

Shamelessly adapted from [@HenrikJoreteg](https://twitter.com/HenrikJoreteg)'s [fixpack](https://github.com/HenrikJoreteg/fixpack) by [@mieky](https://twitter.com/mieky).

## License

MIT
