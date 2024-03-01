# Submitting commits and pull requests

### 1 feature per commit
Features should be kept to a minimum on each commit. Ideally **no more than 1 feature** unless it's related, if not try your best to split it into separate commits. Multiple features are allowed in pull requests however just make sure to stick to **1 feature per commit**.

### Commit/pull request style guide
```
{type}({scope}): {message}
```
E.g:
```
feat(ffmpeg): Add support for ``-c copy`` for faster conversions.
```

Commits should:
- Use code blocks when mentioning things such as code or command line args like so: 

  > fix: ``chick.getNumber()`` returns fake number.

- Be descriptive (like example: Not `added feature`, but instead ``feat: add support for gifs``).
- Use one of the following types:
  - ``feat`` --> a feature (or addition to the source code)
  - ``fix`` --> bug fix
  - ``docs`` --> documentation
  - ``style`` --> formatting, lint stuff
  - ``refactor`` --> code restructure without changing external behaviour
  - ``tests`` --> adding missing tests
  - ``chore`` --> maintenance
  - ``init`` --> initial commit

- Use a comma and then a space to separate types if the commit is related to multiple types (e.g ``fix, tests: Get rid of anime girls, add test to ensure they don't come back.``).
- Be under 100 characters ideally.
- Try to be present tense (e.g ``add something`` not ``added something``).
