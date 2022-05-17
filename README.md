## JSON Subdocument

Sometimes, we want to reduce a JSON document into smaller chunks; containing partial information from this object. Such script would be helpful in many ways:

- Code splitting
- Security

## Checklist

- [ ] Verify document given in config is a subset of the main JSON document
- [ ] Extract document from the main JSON
- [ ] Demos: .gif
- [ ] Test suite: Thorough tests containing all possible cases

## Dependencies

This project uses the following modules:

- [Jest](https://jestjs.io/) for testing
- Node.js [`fs/promises`](https://nodejs.org/api/fs.html#fs_promises_api) module for File System interaction
- AJV schema validation gets executed by another script, not present in this repository. We will update with the link to it once it becomes Open Source.
- [Gulp.js](https://gulpjs.com) Functions for reading and writing files in a pipeline method

## Folder structure

- Entrypoint: [`index.js`](index.js)
- Configuration file: [`config.json`](config.json)
- Configuration file's schema: [`config.schema.json`](config.schema.json)

## Bug reports and suggestions

Bug reports and suggestions are found in the `Issues` part of this repository
