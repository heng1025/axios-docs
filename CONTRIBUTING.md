# Contributing

We are open to, and grateful for, any contributions made by the community. By contributing to axios-docs, you agree to abide by the [code of conduct](https://github.com/axios/axios-docs/blob/master/CODE_OF_CONDUCT.md).

### Code Style

Please follow the [node style guide](https://github.com/felixge/node-style-guide).

### Commit Messages

Commit messages should be verb based, using the following pattern:

- `[Fixed] ...`
- `[Added] ...`
- `[Updated] ...`
- `[Removed] ...`

### Developing

- `npm i -g inert-cli` or `yarn global add inert-cli` to work be able to use the Inert CLI.
- `inert build` to build the documentation.

Please don't include changes to `dist/` in your pull request. This should only be updated when releasing a new version.
