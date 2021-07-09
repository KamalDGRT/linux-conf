# manjaro-conf

Manjaro Configs for various packages.

#### Install packages from a list

To install packages from a previously saved list of packages, while not reinstalling previously
installed packages that are already up-to-date, run:

```
pacman -S --needed - < pacman_pkgs.txt
```

| File                                         | Actual Path                               |
| -------------------------------------------- | ----------------------------------------- |
| [httpd.conf](lampp/httpd.conf)               | `/etc/httpd/conf/httpd.conf`              |
| [httpd-vhosts.conf](lampp/httpd-vhosts.conf) | `/etc/httpd/conf/extra/httpd-vhosts.conf` |
| [php.ini](lampp/php.ini)                     | `/etc/php/php.ini`                        |
| [phpmyadmin.conf](lampp/phpmyadmin.conf)     | `/etc/httpd/conf/extra/phpmyadmin.conf`   |
| [index.html](lampp/index.html)               | `/srv/http/index.html`                    |
| [test.php](lampp/test.php)                   | `/srv/http/test.php`                      |
