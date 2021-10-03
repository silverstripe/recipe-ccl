## Silverstripe Recipe CCL

[![Build Status](https://api.travis-ci.com/silverstripe/recipe-ccl.svg?branch=2)](https://travis-ci.com/silverstripe/recipe-ccl)
[![SilverStripe supported module](https://img.shields.io/badge/silverstripe-supported-0071C4.svg)](https://www.silverstripe.org/software/addons/silverstripe-commercially-supported-module-list/)

This recipe is meant to integrate a Silverstripe CMS project with the underlying infrastructure of Silverstripe Cloud Platform CCL. It's the successor of [`cwp/cwp-recipe-core`](https://github.com/silverstripe/cwp-recipe-core).

This includes the following core Silverstripe CMS modules:

 * [recipe-core](https://github.com/silverstripe/recipe-core): Recipe containing framework, config, assets
 * [cwp-core](https://github.com/silverstripe/cwp-core): CWP basic compatibility module
 * [auditor](https://github.com/silverstripe/silverstripe-auditor): Provides audit trail logging for various events in
   the system
 * [environmentcheck](https://github.com/silverstripe/silverstripe-environmentcheck): Adds automated checks to monitor
   an environment's health status
 * [hybridsessions](https://github.com/silverstripe/silverstripe-hybridsessions): Hybrid cookie/database session store for SilverStripe
 * [mimevalidator](https://github.com/silverstripe/silverstripe-mimevalidator): Checks uploaded file content roughly
   matches a known MIME type for the file extension

This can be either added to an existing project or used as a project base for creating a
basic Silverstripe CMS project.

## Get started

You can create a project using Composer:

```
composer create-project silverstripe/recipe-ccl ./ccl-project ^2
```

## More information

See the [recipe plugin](https://github.com/silverstripe/recipe-plugin) page for instructions on how
SilverStripe recipes work.
