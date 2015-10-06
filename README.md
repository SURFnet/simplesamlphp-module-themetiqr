# simplesamlphp-module-themetiqr
simplesamlphp module for tiqr theme

# Installing the module

## Install using composer

To install in simplesamlphp, use the composer-based [simplesamlphp module installer](https://github.com/simplesamlphp/composer-module-installer)

        $ composer require tiqr/simplesamlphp-module-themetiqr


## Manual Install

Install this theme as follows:

	$ cd simplesamlphp/modules
	$ git clone https://github.com/SURFnet/simplesamlphp-module-themetiqr.git themeTiqr

Edit the main configuration file to enable the theme: change the
following line in `simplesamlphp/config/config.php`:

    'theme.use'             => 'default',

Into:

    'theme.use'             => 'themeTiqr:tiqr',

