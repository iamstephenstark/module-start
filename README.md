# module-start
Basic Magento 2 Module Template

If you just need a quick basic template to start your Magento 2 module you can use this one.

Please update the vendor and module name (ex. IAmStephenStark_Start) to your own and your are ready to go.

## Installation

Copy the contents of **module-start/** to your **app/code/Vendor/ModuleName/** directory. Please update the vendor and module name to what you are using. I will add this to Packagist soon.

Next run the commands below to install it.

    bin/magento module:enable
    bin/magento setup:upgrade
    bin/magento cache:clean


To make sure the module is installed by typing:

    bin/magento module:status IAmStephenStark_Start

## Authors

Contributors names and contact info

[Stephen Stark](iamstephenstark@gmail.com)

## Version History

* 1.0.0
    * Initial Release
