

## Creating and using ssh keys

Video: https://www.youtube.com/watch?v=XCDg1mtaA5I&list=PLpLblYHCzJACyKCfHnPwRruOxllNoHsEg

- What's an ssh key?
- Why is it good to set?
- ssh-keygen -t rsa -b 4096
- Test it:
  ```
  ~$ ssh git@github.com
  PTY allocation request failed on channel 1
  Hi rkdarst! You've successfully authenticated, but GitHub does not provide shell access.
  ```
- Other notes
  - One private key per computer
