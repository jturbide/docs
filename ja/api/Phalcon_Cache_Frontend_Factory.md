# Class **Phalcon\\Cache\\Frontend\\Factory**

*extends* abstract class [Phalcon\Factory](/[[language]]/[[version]]/api/Phalcon_Factory)

*implements* [Phalcon\FactoryInterface](/[[language]]/[[version]]/api/Phalcon_FactoryInterface)

<a href="https://github.com/phalcon/cphalcon/blob/master/phalcon/cache/frontend/factory.zep" class="btn btn-default btn-sm">GitHub上のソース</a>

アダプターオプションを使用してFrontend Cache Adapterクラスをロードします

```php
<?php

use Phalcon\Cache\Frontend\Factory;

$options = [
    "lifetime" => 172800,
    "adapter"  => "data",
];
$frontendCache = Factory::load($options);

```

## メソッド

public static **load** ([Phalcon\Config](/[[language]]/[[version]]/api/Phalcon_Config) | *array* $config)

protected static **loadClass** (*mixed* $namespace, *mixed* $config)

...