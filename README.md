<div align="center">

# asdf-yazi [![Build](https://github.com/PoQuatre/asdf-yazi/actions/workflows/build.yml/badge.svg)](https://github.com/PoQuatre/asdf-yazi/actions/workflows/build.yml) [![Lint](https://github.com/PoQuatre/asdf-yazi/actions/workflows/lint.yml/badge.svg)](https://github.com/PoQuatre/asdf-yazi/actions/workflows/lint.yml)

[yazi](https://yazi-rs.github.io) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add yazi
# or
asdf plugin add yazi https://github.com/PoQuatre/asdf-yazi.git
```

yazi:

```shell
# Show all installable versions
asdf list-all yazi

# Install specific version
asdf install yazi latest

# Set a version globally (on your ~/.tool-versions file)
asdf global yazi latest

# Now yazi commands are available
yazi --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/PoQuatre/asdf-yazi/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Mateo LE FLEM](https://github.com/PoQuatre/)
