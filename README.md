# Magento2 Region Kit

The kit of extensions allows you to manage geographic regions. For each country, you can add the any region, whose name is based on a specific locale. The kit also provides other additional features.

## Children Modules

[Region Api](https://github.com/eriocnemis/m2.RegionApi) - The module serves as application program interface (API) responsible for functionality of regions manage.

[Region Admin Ui](https://github.com/eriocnemis/m2.RegionAdminUi) - The module provides UI for Admin Panel of regions manage as well as bulk operations.

[Region](https://github.com/eriocnemis/m2.Region) - The module is the core of a kit of extensions for regions manage. The module provides basic functionality of regions manage.

[Region Shipping Rule Api](https://github.com/eriocnemis/m2.RegionShippingRuleApi) - The module serves as application program interface (API) responsible for functionality of shipping rules manage as well as bulk operations.

[Region Shipping Rule Admin Ui](https://github.com/eriocnemis/m2.RegionShippingRuleAdminUi) - The module provides UI for Admin Panel of shipping rules manage as well as bulk operations.

[Region Shipping Rule](https://github.com/eriocnemis/m2.RegionShippingRule) - The module allows you to create flexible rules for managing shipping methods depending on the region.

[Region Import](https://github.com/eriocnemis/m2.RegionImport) - The module allows admin to quickly import regions via a CSV file by one click. This simplifies the data update process of regions.

## Compatibility

Version | 2.0.* | 2.1.* | 2.2.* | 2.3.* | 2.4.*
--- | --- | --- | --- | --- | ---
Magento Community | - | - | - | :heavy_check_mark: | :heavy_check_mark:
Magento Enterprise | - | - | - | :heavy_check_mark: | :heavy_check_mark:
Magento Cloud | - | - | - | :heavy_check_mark: | :heavy_check_mark:
Extension version | - | - | - | 2.3.2 | 2.4.1

## Install

#### Install via Composer

1. Go to Magento2 root folder

2. Enter following commands to install module:

     For Magento CE 2.3.x

    ```bash
    composer require eriocnemis/module-region-kit:2.3.*
    ```

   Wait while dependencies are updated.

#### Completion of installation

1. Go to Magento2 root folder

2. Enter following commands:

    ```bash
    php bin/magento setup:upgrade
    php bin/magento setup:di:compile
    php bin/magento setup:static-content:deploy (optional)
    ```

## Uninstall

You can uninstall a module only if you’re certain you won’t use it. Instead of uninstalling a module, you can disable it. Pleace, create backup so you can recover the data at a later time.

#### Uninstall via Composer

1. Go to Magento2 root folder

2. Enter following commands to remove:

    ```bash
    composer remove eriocnemis/module-region-kit
    ```
#### Completion of uninstall

1. Go to Magento2 root folder

2. Enter following commands:

    ```bash
    php bin/magento setup:upgrade
    php bin/magento setup:di:compile
    php bin/magento setup:static-content:deploy (optional)
    ```
## License

All Free Eriocnemis extensions is distributed under the [Open Software License (OSL 3.0)](https://github.com/eriocnemis/m2.Region/blob/master/LICENSE.md), and is thus open source software.

## Contribution

Want to contribute to this extension? The best possibility to provide any code is to open a [pull requests](https://github.com/eriocnemis/m2.Region/pulls) on GitHub. Please, see the [CONTRIBUTING.md](https://github.com/eriocnemis/m2.Region/blob/master/.github/CONTRIBUTING.md) file for more.

## Suggestions

We're also interested in your feedback for the future of our extension. You can submit a suggestion or feature request through the [issue](https://github.com/eriocnemis/m2.Region/issues) tracker. But you must acknowledge and agree that your offer will not prevent Eriocnemis team from using your ideas without obligation to you. General decision will depend on the specific proposal.

## Support

If you encounter any problems or bugs, please open a [issue](https://github.com/eriocnemis/m2.Region/issues). To make this process more effective, we're asking that these include more information to help define them more clearly. Pleace, do not enumerate multiple bugs or feature requests in the same issue. Similarly do not add your issue as a comment to an existing issue. Many issues look similar, but have different causes.

Also note that the issue tracker is not a support forum. If you have questions about how to use the extension, or how to get extension to work, please visit stackoverflow.com.

<p align="center"><img src="https://avatars3.githubusercontent.com/u/48807026?s=48&v=4"></p>
