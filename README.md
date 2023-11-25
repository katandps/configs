# configs

## 1password

see <https://support.1password.com/install-linux/>

## zsh

```sh
curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
eval $(op signin)
op inject -i zsh/.zshrc -o ~/.zshrc
source ~/.zshrc
```
