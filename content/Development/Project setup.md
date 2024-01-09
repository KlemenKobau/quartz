## Conventions
- Use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
  - Many Github actions already implemented
  - Use the following types: `fix:, feat:, build:, chore:, ci:, docs:, style:, refactor:, perf:, test:`
  - `<type>[optional scope]: <description>`

Example:

```
feat(lang): add Polish language
```

Example breaking change:

```
chore!: drop support for Node 6

BREAKING CHANGE: use JavaScript features not available in Node 6.
```

## Changelog
- [Keepachangelog](https://keepachangelog.com/en/1.0.0/) specification
  - Can be automatically generated from Conventional commits.
    - [git-cliff](https://git-cliff.org/) (Looks good)
    - [github-changelog-generator](https://github.com/github-changelog-generator/github-changelog-generator) (Popular)
    - [auto-changelog](https://github.com/cookpete/auto-changelog)
    - [Digital ocean github-changelog-generator](https://github.com/digitalocean/github-changelog-generator)

## Documentation
- [Docusaurus](https://docusaurus.io/), has a Github action, less extensible but looks great
- [MkDocs](https://www.mkdocs.org/), extensible but looks worse
  - [Material gor MkDocs](https://squidfunk.github.io/mkdocs-material/)