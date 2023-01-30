# PHP Reference Generator

###Install

```
composer require timoye/php-reference-generator
```

###Usage

```php
<?php

require_once 'vendor/autoload.php';

use Timoye\ReferenceGenerator;

$token=ReferenceGenerator::getHashedToken();
```

###Credit

http://stackoverflow.com/a/13733588/179104