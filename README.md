# .dotfiles

```none
wget https://raw.githubusercontent.com/brettcurtis/dotfiles/master/.mdlrc
```

```none
wget https://raw.githubusercontent.com/brettcurtis/dotfiles/master/.mdl-rules.rb
```

```none
wget https://raw.githubusercontent.com/brettcurtis/dotfiles/master/.p10k.zsh
```

```none
echo '[[ ! -f ~/.p10k.zsh ]] || source ~/.p10k.zsh' >> ~/.zshrc
```

```none
echo '[[ ! -f ~/.exports ]] || source ~/.exports' >> ~/.zshrc
```

```none
ln -s /mnt/c/Users/brett-home/Desktop desktop
```

```none
git config --global user.email "email@example.com"
```

```none
git config --global user.name "Brett Curtis"
```

```none
git config --global commit.gpgsign true
```


```none
cat << EOF >> ~/.gnupg/gpg-agent.conf
default-cache-ttl 34560000
max-cache-ttl 34560000
EOF
```

## oh-my-zsh-plugins

```none
plugins=(git terraform gcloud aws bundler docker kubectl kubectx gem helm kitchen ubuntu vault zsh-autosuggestions)
```
