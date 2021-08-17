# Description

This module allows you to use livereload for development on your Magento 2 theme 

# Install

`composer require ghostunicorns/module-csp-livereload`

# Attention!

Enable this module only on the local development environment and please add this entry in your staging and production environments `app/etc/env.php` file:
```
...
    'modules' => [
...
        'GhostUnicorns_CspLivereload' => 0,
...
    ],
...
```

# Contribution

Yes, of course you can contribute sending a pull request to propose improvements and fixes.

