# FrontendDevIntermediateExampleModule

This plugin is part of the **Frontend Development Intermediate** learning path.

It demonstrates how to:

- Understand the Shopware administration structure
- Create a basic module with routes and navigation
- Add a simple page with template, SCSS and translations

Tested for **Shopware 6.7**

## Install

Run the following commands to install the plugin:

```bash
bin/console plugin:refresh
bin/console plugin:install FrontendDevIntermediateExampleModule --activate --clearCache
```

Then build the administration and clear the cache:

```bash
bin/build-administration.sh
bin/console cache:clear
```
