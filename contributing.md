# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: this is probably right but this repo is tested with `mise` not `asdf` bump
asdf plugin test templ https://github.com/atahanyorganci/asdf-templ.git "templ --help"
```

Tests are automatically run in GitHub Actions on push and PR.
