PR descriptions and commit messages should follow the 50/72 character rule for title/body line lengths, and follow this format:

```
TITLE

BODY

Refs:
[X] www.example.com

Story: AB#12345,#12345
```

The title of a PR and commit message should be written in present-tense imperative-style, so the history reads like a recipe or a set of instructions.

The format of a PR or commit message title should look like `<WHAT> <WHY> <WHERE>` and be no longer than 50 characters.

The body of a PR description or commit message should keep line length to a maximum of 72 characters.

The body of a PR description or commit message should state the problem and why it is an issue in present-tense.

After stating the issue the PR description or commit message should explain why the solution was selected and how the solution was verified.

References in the body of the PR description and in commit messages should have a reference block like this `[{NUMBER}]`, for example `[1]`. In the `Ref:` section the number of the reference together with the external reference should be listed.

At the bottom of the PR description and commit message there should be a `Story:` section linkng the PR/commit to the relevant story. There should always be two references to a story `AB#1234` and `#1234` so links can be created to both github and external boards.
