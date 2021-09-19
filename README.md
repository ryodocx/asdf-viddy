<div align="center">

# asdf-viddy [![Build](https://github.com/ryodocx/asdf-viddy/actions/workflows/build.yml/badge.svg)](https://github.com/ryodocx/asdf-viddy/actions/workflows/build.yml) [![Lint](https://github.com/ryodocx/asdf-viddy/actions/workflows/lint.yml/badge.svg)](https://github.com/ryodocx/asdf-viddy/actions/workflows/lint.yml)


[viddy](https://github.com/sachaos/viddy) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add viddy
# or
asdf plugin add viddy https://github.com/ryodocx/asdf-viddy.git
```

viddy:

```shell
# Show all installable versions
asdf list-all viddy

# Install specific version
asdf install viddy latest

# Set a version globally (on your ~/.tool-versions file)
asdf global viddy latest

# Now viddy commands are available
viddy --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.
