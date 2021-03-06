# Class **Phalcon\\Annotations\\Adapter\\Apc**

*extends* abstract class [Phalcon\Annotations\Adapter](/[[language]]/[[version]]/api/Phalcon_Annotations_Adapter)

*implements* [Phalcon\Annotations\AdapterInterface](/[[language]]/[[version]]/api/Phalcon_Annotations_AdapterInterface)

<a href="https://github.com/phalcon/cphalcon/blob/master/phalcon/annotations/adapter/apc.zep" class="btn btn-default btn-sm">GitHub上のソース</a>

パースしたアノテーションをAPCに保存します。 このアダプタはプロダクション向けです。

```php
<?php

use Phalcon\Annotations\Adapter\Apc;

$annotations = new Apc();

```

## メソッド

public **__construct** ([*array* $options])

Phalcon\\Annotations\\Adapter\\Apc コンストラクタ

public **read** (*mixed* $key)

パースしたアノテーションをAPCから読み込みます。

public **write** (*mixed* $key, [Phalcon\Annotations\Reflection](/[[language]]/[[version]]/api/Phalcon_Annotations_Reflection) $data)

パースしたアノテーションをAPCに書き込みます。

public **setReader** ([Phalcon\Annotations\ReaderInterface](/[[language]]/[[version]]/api/Phalcon_Annotations_ReaderInterface) $reader) inherited from [Phalcon\Annotations\Adapter](/[[language]]/[[version]]/api/Phalcon_Annotations_Adapter)

アノテーションパーサーを設定します。

public **getReader** () inherited from [Phalcon\Annotations\Adapter](/[[language]]/[[version]]/api/Phalcon_Annotations_Adapter)

アノテーションリーダーを返します。

public **get** (*string* | *object* $className) inherited from [Phalcon\Annotations\Adapter](/[[language]]/[[version]]/api/Phalcon_Annotations_Adapter)

クラス内で見つかったすべてのアノテーションをパースまたは取得します。

public **getMethods** (*mixed* $className) inherited from [Phalcon\Annotations\Adapter](/[[language]]/[[version]]/api/Phalcon_Annotations_Adapter)

そのクラスのすべてのメソッドで見つかったアノテーションを返します。

public **getMethod** (*mixed* $className, *mixed* $methodName) inherited from [Phalcon\Annotations\Adapter](/[[language]]/[[version]]/api/Phalcon_Annotations_Adapter)

そのメソッドで見つかったアノテーションを返します。

public **getProperties** (*mixed* $className) inherited from [Phalcon\Annotations\Adapter](/[[language]]/[[version]]/api/Phalcon_Annotations_Adapter)

そのクラスのすべてのメソッドで見つかったアノテーションを返します。

public **getProperty** (*mixed* $className, *mixed* $propertyName) inherited from [Phalcon\Annotations\Adapter](/[[language]]/[[version]]/api/Phalcon_Annotations_Adapter)

そのプロパティで見つかったアノテーションを返します。