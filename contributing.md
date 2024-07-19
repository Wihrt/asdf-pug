# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test pug https://github.com/Wihrt/asdf-pug.git "pug --version"
```

Tests are automatically run in GitHub Actions on push and PR.
