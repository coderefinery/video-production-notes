

## Configuring Git

Video: https://www.youtube.com/watch?v=WdDTp8NeHBs&list=PLpLblYHCzJACyKCfHnPwRruOxllNoHsEg

- setting my name and email
  `$ git config --global user.name "Your Name"`
  `$ git config --global user.email yourname@example.com`
  `$ git config --global core.editor nano`
    - which email to use?
    - me@users.noreply.github.com
- setting my favorite editor (at least not vi!)
- show where the settings are saved
  - git config --edit --global
  - git config --list --global
- testing it out:
  - create a directory
  - create a file
  - git init
  - git add file
  - git commit
  - git log
