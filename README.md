<div align="center">

# asdf-vmctl [![Build](https://github.com/Davidffry/asdf-vmctl/actions/workflows/build.yml/badge.svg)](https://github.com/Davidffry/asdf-vmctl/actions/workflows/build.yml) [![Lint](https://github.com/Davidffry/asdf-vmctl/actions/workflows/lint.yml/badge.svg)](https://github.com/Davidffry/asdf-vmctl/actions/workflows/lint.yml)

[vmctl](https://github.com/VictoriaMetrics/vmctl) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add vmctl
# or
asdf plugin add vmctl https://github.com/Davidffry/asdf-vmctl.git
```

vmctl:

```shell
# Show all installable versions
asdf list-all vmctl

# Install specific version
asdf install vmctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global vmctl latest

# Now vmctl commands are available
vmctl --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Davidffry/asdf-vmctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [David AUFFRAY](https://github.com/Davidffry/)
