# Robohash

Vector Robohash icons in PHP. Background pictures in PNG and WEBP.

![Robohash](robohash.png)

```php
<?php
require_once 'robohash.php';

echo Robohash::svg('id1', 300, ['clip'=>'circle', 'img_dir'=>'/images/robohash', 'ext'=>'webp']);

echo Robohash::svg('id2', 300, ['clip'=>'hexagon', 'img_dir'=>'/images/robohash', 'ext'=>'png']);

echo Robohash::svg('id3');
```

Links:

1. [Robohash](https://robohash.org/)
2. JS: [robohash](https://github.com/nimiq/robohash)
3. Python: [django-robohash-svg](https://github.com/elapouya/django-robohash-svg)
