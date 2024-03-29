<div align="center">

# asdf-hishtory [![Build](https://github.com/asdf-community/asdf-hishtory/actions/workflows/build.yml/badge.svg)](https://github.com/asdf-community/asdf-hishtory/actions/workflows/build.yml) [![Lint](https://github.com/asdf-community/asdf-hishtory/actions/workflows/lint.yml/badge.svg)](https://github.com/asdf-community/asdf-hishtory/actions/workflows/lint.yml)

[hishtory](https://github.com/ddworken/hishtory) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add hishtory
# or
asdf plugin add hishtory https://github.com/asdf-community/asdf-hishtory.git
```

<YOUR TOOL>:

```shell
# Show all installable versions
asdf list-all hishtory

# Install specific version
asdf install hishtory latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hishtory latest

# Now hishtory commands are available
hishtory --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/asdf-community/asdf-hishtory/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [czchen](https://github.com/czchen/)
