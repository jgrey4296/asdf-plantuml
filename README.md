<div align="center">

# asdf-blah [![Build](https://github.com/jgrey4296/asdf-blah/actions/workflows/build.yml/badge.svg)](https://github.com/jgrey4296/asdf-blah/actions/workflows/build.yml) [![Lint](https://github.com/jgrey4296/asdf-blah/actions/workflows/lint.yml/badge.svg)](https://github.com/jgrey4296/asdf-blah/actions/workflows/lint.yml)

[blah](https://github.com/jgrey4296/blah) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add blah
# or
asdf plugin add blah https://github.com/jgrey4296/asdf-blah.git
```

blah:

```shell
# Show all installable versions
asdf list-all blah

# Install specific version
asdf install blah latest

# Set a version globally (on your ~/.tool-versions file)
asdf global blah latest

# Now blah commands are available
blah --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jgrey4296/asdf-blah/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [John Grey](https://github.com/jgrey4296/)
