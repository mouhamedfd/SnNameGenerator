# Sn Name Generator
```shell
 ____        _   _            ____ 
/ ___| _ __ | \ | |_ __ ___  / ___|
\___ \| '_ \|  \| | '_ ` _ \| |  _ 
 ___) | | | | |\  | | | | | | |_| |
|____/|_| |_|_| \_|_| |_| |_|\____|
___________________________________
```
# Installation
```shell
 composer require "mouhamedfd/sn-name-generator v1.02"
 ```

# Code example
```php
use Mouhamedfd\Generator\SnNameGenerator as SnNmG;
```
## Generate fields
```php
$name=SnNmG::getName();
$firstName=SnNmG::getFirstName();
$firstName=SnNmG::getFirstName('male');
$firstName=SnNmG::getFirstName('female');

```
