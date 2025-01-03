<div align="center">

# mise-spark [![Build](https://github.com/benberryallwood/mise-spark/actions/workflows/build.yml/badge.svg)](https://github.com/benberryallwood/mise-spark/actions/workflows/build.yml) [![Lint](https://github.com/benberryallwood/mise-spark/actions/workflows/lint.yml/badge.svg)](https://github.com/benberryallwood/mise-spark/actions/workflows/lint.yml)

[Apache Spark](https://spark.apache.org/documentation.html) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

## Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

## Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

## Install

Plugin:

```shell
asdf plugin add spark https://github.com/benberryallwood/mise-spark.git
```

spark:

```shell
# Show all installable versions
asdf list-all spark

# Install specific version
asdf install spark latest

# Set a version globally (on your ~/.tool-versions file)
asdf global spark latest

# Now spark commands are available
spark --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

## Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/benberryallwood/mise-spark/graphs/contributors)!

## License

See [LICENSE](LICENSE) © [Ben Berry-Allwood](https://github.com/benberryallwood/)
