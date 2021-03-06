# PHP Git Hooks

[![Total Downloads](https://poser.pugx.org/hexanet/php-git-hooks/downloads.png)](https://packagist.org/packages/hexanet/php-git-hooks) [![Latest Unstable Version](https://poser.pugx.org/hexanet/php-git-hooks/v/unstable.png)](https://packagist.org/packages/hexanet/php-git-hooks)

Features :

* Check if composer.lock is synchronized with composer.json
* Lint
* Check and fix coding styles with PHP-CS-FIXER

![PHP Git Hooks](screenshot.png)

## Installation

```
composer require hexanet/php-git-hooks
```


## Usage

composer.json :

```php
    "scripts": {
        "pre-update-cmd": "Hexanet\\PhpGitHooks\\Composer\\InstallHooksScript::installHooks",
        "pre-install-cmd": "Hexanet\\PhpGitHooks\\Composer\\InstallHooksScript::installHooks"
    }
```

## Credits

Developed by [Hexanet](http://www.hexanet.fr/).

## License

[php-git-hooks](https://github.com/Hexanet/php-git-hooks) is licensed under the [MIT license](LICENSE).
