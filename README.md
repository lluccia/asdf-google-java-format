<div align="center">

# asdf-google-java-format [![Build](https://github.com/lluccia/asdf-google-java-format/actions/workflows/build.yml/badge.svg)](https://github.com/lluccia/asdf-google-java-format/actions/workflows/build.yml) [![Lint](https://github.com/lluccia/asdf-google-java-format/actions/workflows/lint.yml/badge.svg)](https://github.com/lluccia/asdf-google-java-format/actions/workflows/lint.yml)


[google-java-format](https://github.com/google/google-java-format) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add google-java-format
# or
asdf plugin add google-java-format https://github.com/lluccia/asdf-google-java-format.git
```

google-java-format:

```shell
# Show all installable versions
asdf list-all google-java-format

# Install specific version
asdf install google-java-format latest

# Set a version globally (on your ~/.tool-versions file)
asdf global google-java-format latest

# Now google-java-format commands are available
google-java-format --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/lluccia/asdf-google-java-format/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Leandro Conca](https://github.com/lluccia/)
