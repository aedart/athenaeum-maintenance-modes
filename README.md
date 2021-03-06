# Athenaeum Maintenance Modes

Offers a few additional [maintenance modes "drivers"](https://laravel.com/docs/9.x/configuration#maintenance-mode) for Laravel.

```php
// ...somewhere inside your application
$mode = $app->maintenanceMode();
$mode->activate([
    'secret' => '1630542a-246b-4b66-afa1-dd72a4c43515'
]);

// ...etc
```

## Available Modes

* `'array'`: _stores application down state in an array - useful for testing purposes._
* `'json'`: _stores application down state in a json file - very similar to Laravel's default "file based" maintenance mode._

## Documentation

Please read the [official documentation](https://aedart.github.io/athenaeum/) for additional information.

## Repository

The mono repository is located at [github.com/aedart/athenaeum](https://github.com/aedart/athenaeum)

## Versioning

This package follows [Semantic Versioning 2.0.0](http://semver.org/)

## License

[BSD-3-Clause](http://spdx.org/licenses/BSD-3-Clause), Read the LICENSE file included in this package
