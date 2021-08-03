# zshrc_php_brew_switcher

For zsh users who want to change version of php quite easily, the script allows to update the path to the desired version of php.

It is necessary beforehand, to have installed the versions of php with brew. <br>
More information here => https://github.com/shivammathur/homebrew-php


## INSTALL

1. Download file sphp
2. Put it in **/usr/local/bin** or put it somewhere else and make a symbolic link to **/usr/local/bin**
3. Make it executable by running chmod +x /usr/local/bin/sphp

## USAGE


> the script will only modify the following lines by changing the version of php by the one you want.
>>export PATH="/usr/local/opt/php@7.3/bin:$PATH" <br>
>>export PATH="/usr/local/opt/php@7.3/sbin:$PATH"


if you want switch php 7.4 to php 8.0 :

```
sphp 8.0
```
restart your terminal and check version php 
```
php -v 
```
and when if you want rollback to php 7.4, same command : 
```
sphp 7.4
```
restart your terminal and check version php 



