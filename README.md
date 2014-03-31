# fixbow

A bower.json file scrubber for the truly insane, based on [fixpack](https://github.com/HenrikJoreteg/fixpack) by Henrik Joreteg.

It will re-write your bower.json file as follows:

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
- bugs
- homepage
- license

Fix all indenting to 2 spaces.

Oh, and it will tolerate improperly quoted and comma'd JSON thanks to [ALCE](https://npmjs.org/package/alce).

## Usage

1. Install it globally

```
npm i -g fixbow
```

2. Run it in the same directory as your bower.json, that's it.

```
fixbow
```

## Changelog

- 0.0.1 - Initial release

## License

MIT
