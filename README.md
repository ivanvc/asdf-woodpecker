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

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add woodpecker
# or
asdf plugin add woodpecker https://github.com/ivanvc/asdf-woodpecker.git
```

woodpecker:

```shell
# Show all installable versions
asdf list-all woodpecker

# Install specific version
asdf install woodpecker latest

# Set a version globally (on your ~/.tool-versions file)
asdf global woodpecker latest

# Now woodpecker commands are available
woodpecker --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ivanvc/asdf-woodpecker/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ivan Valdes](https://github.com/ivanvc/)
