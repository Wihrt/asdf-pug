<div align="center">

# asdf-pug [![Build](https://github.com/Wihrt/asdf-pug/actions/workflows/build.yml/badge.svg)](https://github.com/Wihrt/asdf-pug/actions/workflows/build.yml) [![Lint](https://github.com/Wihrt/asdf-pug/actions/workflows/lint.yml/badge.svg)](https://github.com/Wihrt/asdf-pug/actions/workflows/lint.yml)

[pug](https://github.com/leg100/pug) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add pug
# or
asdf plugin add pug https://github.com/Wihrt/asdf-pug.git
```

pug:

```shell
# Show all installable versions
asdf list-all pug

# Install specific version
asdf install pug latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pug latest

# Now pug commands are available
pug --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Wihrt/asdf-pug/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Arnaud Hatzenbuhler](https://github.com/Wihrt/)
