run `sudo apt update`

install required extensions for composer
`sudo apt install curl php-cli php-mbstring unzip`

install composer

```bash
cd ~
curl -sS https://getcomposer.org/installer -o composer-setup.php
sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer
```

verify running `composer`
