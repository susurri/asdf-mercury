<div align="center">

# asdf-mercury [![Build](https://github.com/susurri/asdf-mercury/actions/workflows/build.yml/badge.svg)](https://github.com/susurri/asdf-mercury/actions/workflows/build.yml) [![Lint](https://github.com/susurri/asdf-mercury/actions/workflows/lint.yml/badge.svg)](https://github.com/susurri/asdf-mercury/actions/workflows/lint.yml)


[mercury](https://www.mercurylang.org/index.html) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add mercury
# or
asdf plugin add mercury https://github.com/susurri/asdf-mercury.git
```

mercury:

```shell
# Show all installable versions
asdf list-all mercury

# Install specific version
asdf install mercury latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mercury latest

# Now mercury commands are available
mmc --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/susurri/asdf-mercury/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [susurri](https://github.com/susurri/)
