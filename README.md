# .dotfiles

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

## gpg

```none
echo "test" | gpg --pinentry-mode loopback --passphrase "top secret passphrase dude!" --clearsign > /dev/null 2>&1
```
