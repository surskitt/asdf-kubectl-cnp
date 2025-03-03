# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test kubectl-cnp https://github.com/surskitt/asdf-kubectl-cnp.git "kubectl-cnp version"
```

Tests are automatically run in GitHub Actions on push and PR.
