# Reseller API for WP Rocket reseller program

WP Rocket is a WordPress premium caching plugin that provides both lightning speed for your website and easy set up for you.

This library provides connectivity with the WP Rocket Reseller API

Basic usage:

1. Configure your reseller account with your access credentials

`
<?php
$wp_rocket = new WP_Rocket_Reseller('YOUR_APP_EMAIL', 'YOUR_API_KEY');
?>
`

2. Make requests to the API

`
<?php
$wp_rocket = new WP_Rocket_Reseller('YOUR_APP_EMAIL', 'YOUR_API_KEY');
$orders = $wp_rocket->getOrders();
var_dump($orders);
?>
`

## Changelog

### 1.0

* Initial release