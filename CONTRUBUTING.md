# Submitting commits and pull requests
Being open to contribution and modification is what makes open-source software... actually open-source software. So, see a bug? see a possible enchantment? The first thing you should do is **create an issue**. 🚀

### 1 feature per commit
Features should be kept to a minimum on each commit. Ideally **no more than 1 feature** unless it's related, if not try your best to split it into separate commits. Multiple features are allowed in pull requests just beware that this will increase the changes of a pr rejection and us having to continuously request changes. The **1 feature per commit** rule still applies in pull requests.

### Let us know before you waste your time
Always be sure to notify us that you are working on a feature or bug fix before you spend hours programming to then create a pr and find out your feature/fix has already been implemented by another developer. If there isn't already a issue, create one explaining your issue, then ideally ask for our opinions / suggestions before implementing production code as this will increase the changes of that said code getting merged into the codebase.

Of course feel free to experiment and implement all you want, just be sure to know that just because you've spent hours working on a feature doesn't mean we'll be keen to merge it.

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

#### Don't think too hard about it! We have much tolerance for newcomers.
Happy contributing!
