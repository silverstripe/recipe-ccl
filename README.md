## CWP Core Recipe

Core functionality only recipe for a [CWP 2.0](https://www.cwp.govt.nz) installation. This includes the following core
SilverStripe and CWP modules:

 * [recipe-core](https://github.com/silverstripe/recipe-core): Recipe containing framework, config, assets
 * [auditor](https://github.com/silverstripe/silverstripe-auditor): Provides audit trail logging for various events in
   the system
 * [environmentcheck](https://github.com/silverstripe/silverstripe-environmentcheck): Adds automated checks to monitor
   an environment's health status

This can be either added to an existing project or used as a project base for creating a
basic CWP core-only install.

## Get started

You can create a project using Composer:

```
composer create-project cwp/cwp-recipe-core ./cwp2-core ^2@dev
```

## More information

See the [recipe plugin](https://github.com/silverstripe/recipe-plugin) page for instructions on how
SilverStripe recipes work.
