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

This tool depends on java 17 or greater, and the java executable must be in the PATH.

Java can be installed using asdf
```
asdf plugin-add java
asdf install java temurin-17.0.5+8
asdf global java temurin-17.0.5+8 
```

- `bash`, `curl`, `tar`: generic POSIX utilities.

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
