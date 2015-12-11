# ColorBashPrompt

[![Total Downloads](https://poser.pugx.org/m4rc1no5/color-bash-prompt/downloads)](https://packagist.org/packages/m4rc1no5/color-bash-prompt)

Color your bash commands

Documentation
=============

Table of contents
-----------------

1. [Installation](#installation)
2. [Examples](#examples)

<a name="installation"></a>
Installation
------------

ColorBashPrompt is available at packagist.org, so you can use composer to download this library and all dependencies.

*(add to require section in your composer.json file)*

```json
    {
        "require": {
            "m4rc1no5/color-bash-prompt": "@dev"
        }
    }
```

<a name="examples"></a>
Examples
--------

```php
// create ColorBashPrompt
$cbp = new ColorBashPrompt();

//yellow text in console
echo $cbp->writeln("Yellow text", ColorBashPrompt::YELLOW);
```