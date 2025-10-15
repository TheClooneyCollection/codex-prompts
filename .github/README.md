# Codex Prompt

My super powered custom Codex Prompts

## Install

```bash
git clone https://github.com/TheClooneyCollection/codex-prompts.git ~/.codex/prmopts
```

## Prompts

### **Release**

Coordinates tagging and publishing a new release with `git` and `gh`.

- review commits since last release and propose a semantic version
- craft the `<Project>: <Version> - <Title>` release title and description
- bump package metadata to the new version and commit the change
- prepare to tag and push, then wait for review before running tagging or `gh release` commands

### **PR**

Prepares the title and description of a pull request prior to using `gh`.

- check the branch commits to shape an accurate PR title
- write a description scaled to the complexity of the changes
- propose reviewer guidance when the diff is substantial
- pause for review before running any `gh` commands to open the PR
