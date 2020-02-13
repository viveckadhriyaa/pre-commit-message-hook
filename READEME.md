# Conventional commit hooks

[https://github.com/commutatus/git-hooks-templates.git](https://github.com/viveckadhriyaa/pre-commit-message-hook.git)

There's one hook attached in this directory that checks for conventional commits

### How to use

Hooks reside in every repo's .git/hooks directory. All hooks are added with `.sample` extension which restricts them to execute by default. By removing you can install the hook you want to execute.

`pre-commit-msg.sample` to `pre-commit-msg`

To make the hook executable you have to run this command

`chmod +x prepare-commit-msg`

Then copy and paste the code written in `pre-commit-message` file from this repository