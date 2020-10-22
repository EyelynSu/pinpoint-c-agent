## Steps

* copy pinpoint header into index.php

```php
define('AOP_CACHE_DIR', __DIR__ . '/../Cache/');
define('PLUGINS_DIR', __DIR__ . '/../Plugins/');
define('APPLICATION_NAME','app-yii2');
define('APPLICATION_ID','app-yii2');
define('PINPOINT_USE_CACHE','YES');
define('PP_REQ_PLUGINS', '\Plugins\Framework\yii2\Yii2ReqPlugins');
require_once __DIR__ . '/../vendor/pinpoint-apm/pinpoint-php-aop/auto_pinpointed.php';

```

* copy setting.ini into `Plugins`