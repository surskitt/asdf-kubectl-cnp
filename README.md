<div align="center">

# asdf-kubectl-cnp [![Build](https://github.com/surskitt/asdf-kubectl-cnp/actions/workflows/build.yml/badge.svg)](https://github.com/surskitt/asdf-kubectl-cnp/actions/workflows/build.yml) [![Lint](https://github.com/surskitt/asdf-kubectl-cnp/actions/workflows/lint.yml/badge.svg)](https://github.com/surskitt/asdf-kubectl-cnp/actions/workflows/lint.yml)

[kubectl-cnp](https://github.com/EnterpriseDB/kubectl-cnp) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add kubectl-cnp
# or
asdf plugin add kubectl-cnp https://github.com/surskitt/asdf-kubectl-cnp.git
```

kubectl-cnp:

```shell
# Show all installable versions
asdf list-all kubectl-cnp

# Install specific version
asdf install kubectl-cnp latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kubectl-cnp latest

# Now kubectl-cnp commands are available
kubectl-cnp version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/surskitt/asdf-kubectl-cnp/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [surskitt](https://github.com/surskitt/)
