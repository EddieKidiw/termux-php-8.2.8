# termux-php-8.2.8
Termux downgrade php 8.3.4 to 8.2.8

# WARNING
save your data before downgrading php version [Backing_up_Termux](https://wiki.termux.com/wiki/Backing_up_Termux)

## Get termux architecture
```bash
dpkg --print-architecture
```

## install
```bash
dpkg -i path/to/php_8.2.8-2_XXX.deb.deb
```
or
```bash
dpkg -i php_8.2.8-2_XXX.deb.deb
```

## check php version
```bash
php -v
```
