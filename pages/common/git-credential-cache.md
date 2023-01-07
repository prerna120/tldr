# git credential-cache

> `git` helper to temporarily store passwords in memory.
> More information: <https://git-scm.com/docs/git-credential-cache>.

- Store Git credentials for a specific amount of time:

`git config credential.helper 'cache --timeout={{1..infinity}}'`