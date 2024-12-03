<div align="center">

# asdf-ripsecrets [![Build](https://github.com/boris-smidt-klarrio/asdf-ripsecrets/actions/workflows/build.yml/badge.svg)](https://github.com/boris-smidt-klarrio/asdf-ripsecrets/actions/workflows/build.yml) [![Lint](https://github.com/boris-smidt-klarrio/asdf-ripsecrets/actions/workflows/lint.yml/badge.svg)](https://github.com/boris-smidt-klarrio/asdf-ripsecrets/actions/workflows/lint.yml)

[ripsecrets](https://github.com/sirwart/ripsecrets) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add ripsecrets
# or
asdf plugin add ripsecrets https://github.com/boris-smidt-klarrio/asdf-ripsecrets.git
```

ripsecrets:

```shell
# Show all installable versions
asdf list-all ripsecrets

# Install specific version
asdf install ripsecrets latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ripsecrets latest

# Now ripsecrets commands are available
ripsecrets --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/boris-smidt-klarrio/asdf-ripsecrets/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Boris Smidt](https://github.com/boris-smidt-klarrio/)
