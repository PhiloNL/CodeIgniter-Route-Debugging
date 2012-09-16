CodeIgniter-Route-Debugging
===========================

###Installation
Clone file to application/core/MY_Router.php

Open application/config/config.php and change the log treshold:

`$config['log_threshold'] = 2;`

###Log

All routes will be logged inside application/logs and will look like:

```
DEBUG --> Client sent : product/laptop
DEBUG --> Route found : product/(:any)  --> shop/view_product/$1
DEBUG --> Redirecting to : product/laptop  --> shop/view_product/laptop
```
