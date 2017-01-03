# mackerel-client-php

mackerel-client-php is an unofficial port of [mackerelio/mackerel-client-ruby](https://github.com/mackerelio/mackerel-client-ruby).

## Usage

```php
<?php

require __DIR__ . '/vendor/autoload.php';

$client = new \Mackerel\Client([
    'mackerel_api_key' => 'YOUR_MACKEREL_API_KEY_HERE',
]);
$host = $client->getHost('HOST_ID');
```

## License

MIT

## Author

[ariarijp](https://github.com/ariarijp)