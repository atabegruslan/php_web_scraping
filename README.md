# Web Scraping with plain PHP

https://www.youtube.com/watch?v=fABDulzEH1c

https://sourceforge.net/projects/simplehtmldom/

```php
<?php

include('simple_html_dom.php');

$url = "xxx";
$html = file_get_html($url); // Type Simple_HTML_DOM_Node
$occurances = $html->find('.classname');
```

# Web Scraping with plain PHP - My Example

https://github.com/atabegruslan/php_web_scraping/blob/master/memriserussian.php
