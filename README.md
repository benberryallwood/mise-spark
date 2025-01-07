<div align="center">

# mise-spark [![Build](https://github.com/benberryallwood/mise-spark/actions/workflows/build.yml/badge.svg)](https://github.com/benberryallwood/mise-spark/actions/workflows/build.yml) [![Lint](https://github.com/benberryallwood/mise-spark/actions/workflows/lint.yml/badge.svg)](https://github.com/benberryallwood/mise-spark/actions/workflows/lint.yml)

[Apache Spark](https://spark.apache.org/documentation.html) plugin for the [mise version manager](https://mise.jdx.dev).

</div>

## Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

## Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

## Install

Plugin:

```shell
mise plugins install spark https://github.com/benberryallwood/mise-spark.git
```

spark:

```shell
# Show all installable versions
mise ls-remote spark

# Install specific version
mise install spark@latest

# Set a version globally (on your ~/.config/mise/config.toml file)
mise use --global spark@latest

# Now spark commands are available
spark-shell --help
```

Check [mise](https://mise.jdx.dev) docs for more instructions on how to install & manage versions.

## Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/benberryallwood/mise-spark/graphs/contributors)!

## License

See [LICENSE](LICENSE) © [Ben Berry-Allwood](https://github.com/benberryallwood/)
