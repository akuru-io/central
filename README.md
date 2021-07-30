# Akuru Central

## Developer Guide

### Getting Started

```
git clone git@github.com:akuru-io/central.git akuru-central
cd akuru-central
npm run setup // this will install all the dependecies and initialize git-submodule
```

This will pull all the support repositoies into a same workspace.

#### Contributing

- Primary branch is `master`, and strongly recommend to avoid pushing changes to `master` branch directly.
- Always use feature branches.
- Alyways put active WIP PRs in draft stage

##### Branch names
- Use `feat/<awasome-feature>-[issue-id]` naming conventions for feature branches
- Use `fix/<good-fix>-[issue-id]` for bug fixes
- Use `chore/<task>-[issue-id]` for regular tasks

##### PR naming
- Use `feat: <My Awesome Feature>` naming conventions for feature titles
- Use `fix: <That fix>` for fixes
- Use `chore: <Regular Task>` for regular tasks

##### Commit messages
- Follow these guidelines
  - [How to Write a Git Commit Message by Chris Beams](https://chris.beams.io/posts/git-commit/)
  - [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
  
##### Issues
Apply labels appropriately for each issues when created:

- `epic`
- `story`
- `bug`
- `feature`
- `feature-request`
- `enhancement`
- `documentation`
- `question`
- `help wanted`

Components:

- `comp:cli`
- `comp:api`
- `comp:client`

Labels for maintainers

- `wontfix`
- `invalid`
- `good first issue`
- `duplicate`

Priorities

- `priority:high`
- `priority:medium`
- `priority:low`
