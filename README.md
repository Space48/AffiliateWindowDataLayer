# Affiliate Window Data Layer

An Affiliate Window module for Magento that integrates with our GTM DataLayer module: https://github.com/Space48/GtmDataLayer - it adds the following data layer variables:

### Order Success

- test_mode

## Installation

**Manual**

To install this module copy the code from this repo to `app/code/Space48/AffiliateWindowDataLayer` folder of your Magento 2 instance, then you need to run php `bin/magento setup:upgrade`

**Composer**:

From the terminal execute the following:

`composer config repositories.space48-affiliatewindow-datalayer vcs git@github.com:Space48/AffiliateWindowDataLayer.git`

then

`composer require "space48/affiliatewindowdatalayer:dev-master"`

## How to use it

Go to `Stores > Configuration > Space48 > GTM DataLayer > Affiliate Window` to configure/enable.