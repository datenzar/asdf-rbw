<div align="center">

# asdf-rbw [![Build](https://github.com/datenzar/asdf-rbw/actions/workflows/build.yml/badge.svg)](https://github.com/datenzar/asdf-rbw/actions/workflows/build.yml) [![Lint](https://github.com/datenzar/asdf-rbw/actions/workflows/lint.yml/badge.svg)](https://github.com/datenzar/asdf-rbw/actions/workflows/lint.yml)

[rbw](https://github.com/doy/rbw) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add rbw
# or
asdf plugin add rbw https://github.com/datenzar/asdf-rbw.git
```

rbw:

```shell
# Show all installable versions
asdf list-all rbw

# Install specific version
asdf install rbw latest

# Set a version globally (on your ~/.tool-versions file)
asdf global rbw latest

# Now rbw commands are available
rbw --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/datenzar/asdf-rbw/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Martin Kleine](https://github.com/datenzar/)
