# Magento 2 Module MgtWizards WizCaptcha

    ``mgtwizards/module-wizcaptcha``

-   [Main Functionalities](#markdown-header-main-functionalities)
-   [Installation](#markdown-header-installation)
-   [Configuration](#markdown-header-configuration)
-   [Specifications](#markdown-header-specifications)

## Main Functionalities

Simple math captcha for customer registration page. Can work together with reCaptcha.

Example here: https://mgt-wizards.com/customer/account/create/

Module available to download here: https://mgt-wizards.com/simple-math-captcha-for-magento-2

## Installation

\* = in production please use the `--keep-generated` option

### Type 1: Zip file

-   Unzip the zip file in `app/code/MgtWizards/WizCaptcha`
-   Enable the module by running `php bin/magento module:enable MgtWizards_WizCaptcha`
-   Apply database updates by running `php bin/magento setup:upgrade`\*
-   Flush the cache by running `php bin/magento cache:flush`

## Configuration

Once installed, should appear instantly at customer registration page.

## Specifications

-   Plugin
    -   beforeExecute - Magento\Customer\Controller\Account\CreatePost > MgtWizards\WizCaptcha\Plugin\Magento\Customer\Controller\Account\CreatePost
