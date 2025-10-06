<div align="center">

# asdf-plantuml[![Build](https://github.com/jgrey4296/asdf-plantuml/actions/workflows/build.yml/badge.svg)](https://github.com/jgrey4296/asdf-plantuml/actions/workflows/build.yml) [![Lint](https://github.com/jgrey4296/asdf-plantuml/actions/workflows/lint.yml/badge.svg)](https://github.com/jgrey4296/asdf-plantuml/actions/workflows/lint.yml)

[plantuml](https://plantuml.com) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `grep`
- `awk`
- `java`
- `asdf` version 0.18.0

# Install

Plugin:

```shell
asdf plugin add plantuml https://github.com/jgrey4296/asdf-plantuml.git
```

plantuml:

```shell
# Show all installable versions
asdf list all plantuml

# Install specific version
asdf install plantuml 1.2025.8

# Set a version globally (on your ~/.tool-versions file)
asdf set plantuml 1.2025.8

# Now plantuml commands are available
plantuml --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# License

See [LICENSE](LICENSE) © [John Grey](https://github.com/jgrey4296/)
