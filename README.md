<div align="center">

# asdf-aws-vault [![Build](https://github.com/FormidableLabs/asdf-aws-vault/actions/workflows/build.yml/badge.svg)](https://github.com/FormidableLabs/asdf-aws-vault/actions/workflows/build.yml) [![Lint](https://github.com/FormidableLabs/asdf-aws-vault/actions/workflows/lint.yml/badge.svg)](https://github.com/FormidableLabs/asdf-aws-vault/actions/workflows/lint.yml)


[aws-vault](https://github.com/FormidableLabs/aws-vault) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add aws-vault
# or
asdf plugin add aws-vault https://github.com/FormidableLabs/asdf-aws-vault.git
```

aws-vault:

```shell
# Show all installable versions
asdf list-all aws-vault

# Install specific version
asdf install aws-vault latest

# Set a version globally (on your ~/.tool-versions file)
asdf global aws-vault latest

# Now aws-vault commands are available
aws-vault --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/FormidableLabs/asdf-aws-vault/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tyler Thompson](https://github.com/FormidableLabs/)
