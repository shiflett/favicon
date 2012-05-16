A library to determine a site's favicon
=======================================

Requirements
------------

- [PHP] (http://php.net/)

Usage
-----

    <?php

    include 'favicon.php';

    $favicon = new Favicon();

    echo $favicon->get('http://shiflett.org/');

    ?>