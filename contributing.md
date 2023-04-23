# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test mercury https://github.com/susurri/asdf-mercury.git "mmc --version"
```

Tests are automatically run in GitHub Actions on push and PR.
