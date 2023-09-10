<div align="center">

# asdf-lsd [![Build](https://github.com/ossareh/asdf-lsd/actions/workflows/build.yml/badge.svg)](https://github.com/ossareh/asdf-lsd/actions/workflows/build.yml) [![Lint](https://github.com/ossareh/asdf-lsd/actions/workflows/lint.yml/badge.svg)](https://github.com/ossareh/asdf-lsd/actions/workflows/lint.yml)

[lsd](https://github.com/lsd-rs/lsd) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add lsd
# or
asdf plugin add lsd https://github.com/ossareh/asdf-lsd.git
```

lsd:

```shell
# Show all installable versions
asdf list-all lsd

# Install specific version
asdf install lsd latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lsd latest

# Now lsd commands are available
lsd --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ossareh/asdf-lsd/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [P. Michael Ossareh](https://github.com/ossareh/)
