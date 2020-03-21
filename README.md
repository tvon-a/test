# Test

Just confirming git for this new account is setup as desired.

## SSH Config

This is my first run at having multiple GitHub accounts (personal and work).

Key bits:

```console
$ ssh-keygen -f ~/.ssh/id_rsa.tvon-a-github
# ....
```

Update `~/.ssh/config` with:

```
Host github.com
   HostName github.com
   User git
   IdentityFile ~/.ssh/id_rsa.tvon-a-github
```

GPG setup is the same as with the inital account, just gen a new key.
