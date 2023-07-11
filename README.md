<div align="center">

# asdf-yugabyte [![Build](https://github.com/GRoguelon/asdf-yugabyte/actions/workflows/build.yml/badge.svg)](https://github.com/GRoguelon/asdf-yugabyte/actions/workflows/build.yml) [![Lint](https://github.com/GRoguelon/asdf-yugabyte/actions/workflows/lint.yml/badge.svg)](https://github.com/GRoguelon/asdf-yugabyte/actions/workflows/lint.yml)

[yugabyte](https://github.com/GRoguelon/yugabyte) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add yugabyte
# or
asdf plugin add yugabyte https://github.com/GRoguelon/asdf-yugabyte.git
```

yugabyte:

```shell
# Show all installable versions
asdf list-all yugabyte

# Install specific version
asdf install yugabyte latest

# Set a version globally (on your ~/.tool-versions file)
asdf global yugabyte latest

# Now yugabyte commands are available
yugabyte --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/GRoguelon/asdf-yugabyte/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Geoffrey Roguelon](https://github.com/GRoguelon/)
