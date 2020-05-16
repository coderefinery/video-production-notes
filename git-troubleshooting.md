

## Troubleshooting Git configuration

Video: https://www.youtube.com/watch?v=B27pUBrWp5w&list=PLpLblYHCzJACyKCfHnPwRruOxllNoHsEg

- troubleshooting
  - name and email not set at all
      - `git commit --amend --reset-author`
  - "wrong" editor opens up
  - editor closes immediately with an empty commit message abort

We did not talk about the below

- no git log (conda on windows?)
  - We don't know how to reproduce it
- Is ~/.gticonfig usable on windows?
  - `git config --global --edit` instead of `nano ~/.gitconfig` to be more portable?
     But... then you don't know how to edit it to fix
