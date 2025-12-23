<div align="center">

# asdf-curlie [![Build](https://github.com/remmercier/asdf-curlie/actions/workflows/build.yml/badge.svg)](https://github.com/remmercier/asdf-curlie/actions/workflows/build.yml) [![Lint](https://github.com/remmercier/asdf-curlie/actions/workflows/lint.yml/badge.svg)](https://github.com/remmercier/asdf-curlie/actions/workflows/lint.yml)

[curlie](https://github.com/rs/curlie) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `git` and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add curlie
# or
asdf plugin add curlie https://github.com/remmercier/asdf-curlie.git
```

curlie:

```shell
# Show all installable versions
asdf list-all curlie

# Install specific version
asdf install curlie latest

# Set a version globally (on your ~/.tool-versions file)
asdf global curlie latest

# Now curlie commands are available
curlie --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/remmercier/asdf-curlie/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Rémi Mercier](https://github.com/remmercier/)
