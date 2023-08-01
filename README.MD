curl -s https://raw.githubusercontent.com/keenser/repo/master/PUBLIC.KEY | sudo gpg --no-default-keyring --keyring gnupg-ring:/etc/apt/trusted.gpg.d/keenser.github.io.gpg --import

apt sources.list:
```
echo "deb http://repo.grsk.eu.org stable main" | sudo tee /etc/apt/sources.list.d/grsk.list
```
