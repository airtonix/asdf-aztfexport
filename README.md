<div align="center">

# asdf-aztfexport [![Build](https://github.com/airtonix/asdf-aztfexport/actions/workflows/build.yml/badge.svg)](https://github.com/airtonix/asdf-aztfexport/actions/workflows/build.yml) [![Lint](https://github.com/airtonix/asdf-aztfexport/actions/workflows/lint.yml/badge.svg)](https://github.com/airtonix/asdf-aztfexport/actions/workflows/lint.yml)

[aztfexport](https://github.com/Azure/aztfexport) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add aztfexport
# or
asdf plugin add aztfexport https://github.com/airtonix/asdf-aztfexport.git
```

aztfexport:

```shell
# Show all installable versions
asdf list-all aztfexport

# Install specific version
asdf install aztfexport latest

# Set a version globally (on your ~/.tool-versions file)
asdf global aztfexport latest

# Now aztfexport commands are available
aztfexport --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/airtonix/asdf-aztfexport/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Zeno Jiricek](https://github.com/airtonix/)
