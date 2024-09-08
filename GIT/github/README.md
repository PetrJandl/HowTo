
### Public key to github
Setting -> SSH and GPG keys
https://github.com/settings/keys

### GPG keys

#### Generate new key
```bash
gpg --full-generate-key
```
#### List od exist keys
```bash
gpg --list-secret-keys --keyid-format=long
```
#### Export any key by ID (sec XXXX/ID)
```bash
gpg --armor --export ID
```
#### Set global GPG
```bash
git config --global user.signingkey XXX
```
#### Set GPG only for this project
```bash
git config user.signingkey XXX
```


