---
description: Setup modules via FTP or cPanel upload files
---

# Upload files installation

## Upload module files to the server

Before start, you should download module file on download page before \(https://landofcoder.com\)

Choose module version file for magento 2 version, example use version for magento 2.4.2:

The module require setup there sub modules:

Ves All, Ves Setup , Ves Base Widgets, Ves Page Builder

* Run magento 2 commands for setup:

```
$ php bin/magento setup:upgrade 
$ php bin/magento setup:static-content:deploy -f
$ php bin/magento cache:clean
```

{% hint style="info" %}
 If your site are running production mode, please remove old generated static files and re run set production mode command.
{% endhint %}



