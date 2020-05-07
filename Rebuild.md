# Rebuild

0. Hide the dock

1. Remap keyboard shorcuts
- caps lock => control

1. Transfer ssh keys from ~/.ssh

2. Add ssh key to keychain, like this:
- Edit ~/.ssh/config:
```
Host *
  AddKeysToAgent yes
  UseKeychain yes
  IdentityFile ~/.ssh/id_rsa
```
- then `ssh-add -K ~/.ssh/id_rsa`

3. Change hostname: `sudo scutil --set HostName [NewHostNameHere]`

5. Install brew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

1. Install brew and brew casks

4. Change default shell
```
$ sudo echo "$(which zsh)" >> /etc/shells
$ chsh -s $(which zsh)
```

1. Install `vcprompt` -> `bin/vcprompt-install`

