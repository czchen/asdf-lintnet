<div align="center">

# asdf-lintnet [![Build](https://github.com/asdf-community/asdf-lintnet/actions/workflows/build.yml/badge.svg)](https://github.com/asdf-community/asdf-lintnet/actions/workflows/build.yml) [![Lint](https://github.com/asdf-community/asdf-lintnet/actions/workflows/lint.yml/badge.svg)](https://github.com/asdf-community/asdf-lintnet/actions/workflows/lint.yml)

[lintnet](https://lintnet.github.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add lintnet
# or
asdf plugin add lintnet https://github.com/asdf-community/asdf-lintnet.git
```

lintnet:

```shell
# Show all installable versions
asdf list-all lintnet

# Install specific version
asdf install lintnet latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lintnet latest

# Now lintnet commands are available
lintnet --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/asdf-community/asdf-lintnet/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [ChangZhuo Chen (陳昌倬) <czchen@czchen.org>](https://github.com/czchen/)
