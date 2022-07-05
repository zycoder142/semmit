# Semmit

_Semantic Message Commit_

Message that conforms to the conventional commit standard:

- `chore(UnknownScope):` for task-related files, such as: dotfiles, licenses, config, etc.
- `fix(UnknownScope):` for a bug fix for the user, not a fix to a build script. Such commit will trigger a release bumping a PATCH version.
- `feat(script):` for a new algorithm feature for the user, not a new feature for build script. Such commit will trigger a release bumping a MINOR version.
- `feature(UnknownScope):` for add the latest features.
- `perf(UnknownScope):` for performance improvements. Such commit will trigger a release bumping a PATCH version.
- `style(format):` for formatting changes, missing semicolons, etc.
- `style(ui):` for to change the user interface style.
- `test(UnknownScope):` for adding missing tests, refactoring tests; no production code change.
- `refactor(UnknownScope):` for refactoring production code but do not change its function, e.g. renaming a variable.
- `docs(readme):` for changes to the documentation.

__for the `UnknownScope` section, you can change which part of the scope you are working on__

Referensi: [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/), [Karma Runner](https://karma-runner.github.io/6.3/dev/git-commit-msg.html), [Sparkbox](https://sparkbox.com/foundry/semantic_commit_messages)

### Usage examples

```git commit -m "docs(readme): add documentation"```

```git commit -m  "feat(meta): add favicon and meta informations for social media"```
