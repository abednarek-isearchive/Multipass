# Multipass
Multipass is a reference tool intended for researchers to demonstrate how to extract secrets from locked password managers on the Windows platform.

Terminology:
A password manager exists in 3 possible states:
1)	Not running – the password manager has been configured with a master password and secret and contains password entries. However, the process is not running – all secrets are supposed to remain on disk encrypted.
2)	Running Unlocked – The password manager has been unlocked using the master password and a user can interact with entries to view/edit contents.
3)	Running Locked – The password manager was previously ‘Running Unlocked’ but has been placed into a locked state where the master password must be entered to place it into a ‘Running Unlocked’ State.


In a running locked state, the master password is recoverable from:
* 1Password 4
* 1Password 7
* LastPass for Applications

In a running locked state, one or more entries are recoverable from:
* 1Password 4
* 1Password 7
* LastPass for Applications
* Dashlane
* KeePass 2

