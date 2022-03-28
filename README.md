# Usage
```php 
require_once('router.php');

$url = $_SERVER['REQUEST_URI']

$routes = [
  '/' => 'functions/homepage.php',
  '/about' => 'functions/about.php',
  '/me' => 'me.php'
];
```

## Set routing
```php 
router::check(string $url, array $routes);
```
