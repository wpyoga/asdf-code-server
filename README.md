<div align="center">

# asdf-code-server [![Build](https://github.com/wpyoga/asdf-code-server/actions/workflows/build.yml/badge.svg)](https://github.com/wpyoga/asdf-code-server/actions/workflows/build.yml) [![Lint](https://github.com/wpyoga/asdf-code-server/actions/workflows/lint.yml/badge.svg)](https://github.com/wpyoga/asdf-code-server/actions/workflows/lint.yml)


[code-server](https://coder.com/docs/code-server/latest/guide) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add code-server
# or
asdf plugin add code-server https://github.com/wpyoga/asdf-code-server.git
```

code-server:

```shell
# Show all installable versions
asdf list-all code-server

# Install specific version
asdf install code-server latest

# Set a version globally (on your ~/.tool-versions file)
asdf global code-server latest

# Now code-server commands are available
code-server --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/wpyoga/asdf-code-server/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [William Poetra Yoga](https://github.com/wpyoga/)
