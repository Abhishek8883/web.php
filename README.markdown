# What is web.php?

*web.php* is a simple and minimalistic front controller based model-view-controller implementation for PHP.

## Hello World in web.php

    <?php
    include 'web.php';
    get('/', function() {
        die('Hello, World!');
    });