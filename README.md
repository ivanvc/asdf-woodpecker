<div align="center">

# asdf-woodpecker [![Build](https://github.com/ivanvc/asdf-woodpecker/actions/workflows/build.yml/badge.svg)](https://github.com/ivanvc/asdf-woodpecker/actions/workflows/build.yml) [![Lint](https://github.com/ivanvc/asdf-woodpecker/actions/workflows/lint.yml/badge.svg)](https://github.com/ivanvc/asdf-woodpecker/actions/workflows/lint.yml)

[woodpecker](https://github.com/woodpecker-ci/woodpecker) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add woodpecker-cli
# or
asdf plugin add woodpecker-cli https://github.com/ivanvc/asdf-woodpecker.git
```

woodpecker:

```shell
# Show all installable versions
asdf list-all woodpecker-cli

# Install specific version
asdf install woodpecker-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global woodpecker-cli latest

# Now woodpecker-cli commands are available
woodpecker-cli --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ivanvc/asdf-woodpecker/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ivan Valdes](https://github.com/ivanvc/)
