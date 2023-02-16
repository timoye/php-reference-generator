# PHP Reference Generator

### Install

Generate unique references in your php project

```
composer require timoye/php-reference-generator:dev-master
```

### Usage

```php
<?php

require_once 'vendor/autoload.php';

use Timoye\ReferenceGenerator;

$token=ReferenceGenerator::getHashedToken();

#default length is 25

string(25) "0VE5EVWFXegzllH9mymWeUyHg"

string(25) "ieKIj4fkXXM2S2d2ZlsfN51Wp"

string(25) "NLN92yVlQ2K5c7tb0Ybd0iMDJ"


#You can define your reference length

$token=ReferenceGenerator::getHashedToken(7);

string(7) "FbKnCn7"

string(7) "Qkspgrd"

string(7) "riflXQN"

```

### Credit

http://stackoverflow.com/a/13733588/179104
