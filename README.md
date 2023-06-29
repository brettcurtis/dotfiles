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
echo '[[ ! -f  /usr/share/zsh/site-functions/zsh-syntax-highlighting.zsh ]] || source /usr/share/zsh/site-functions/zsh-syntax-highlighting.zsh' >> ~/.zshrc
```

```none
echo '[[ ! -f ~/.p10k.zsh ]] || source ~/.p10k.zsh' >> ~/.zshrc
```

```none
echo '[[ ! -f ~/.exports ]] || source ~/.exports' >> ~/.zshrc
```

```none
ln -s /mnt/c/Users/brett/Desktop desktop
```

```none
git config --global user.email "brett@example.com"
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
plugins=(git terraform gcloud bundler docker kubectl gem helm kitchen vault zsh-autosuggestions)
```

## gpg

```none
echo "test" | gpg --pinentry-mode loopback --passphrase "top secret passphrase dude!" --clearsign > /dev/null 2>&1
```
