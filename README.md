# magento2-weltpixel-newsletter-lite

### Installation

Dependencies:
- magento2-weltpixel-backend (see https://github.com/Weltpixel/magento2-weltpixel-backend)
- magento2-weltpixel-mobiledetect (see https://github.com/Weltpixel/magento2-weltpixel-mobiledetect)

With composer:

```sh
$ composer config repositories.weltpixel-magento2-weltpixel-backend git https://github.com/Weltpixel/magento2-weltpixel-backend.git
$ composer require weltpixel/magento2-weltpixel-backend:dev-master

$ composer config repositories.weltpixel-magento2-weltpixel-mobiledetect git https://github.com/Weltpixel/magento2-weltpixel-mobiledetect.git
$ composer require weltpixel/magento2-weltpixel-mobiledetect:dev-master

$ composer config repositories.weltpixel-magento2-weltpixel-newsletter-lite git https://github.com/Weltpixel/magento2-weltpixel-newsletter-lite.git
$ composer require weltpixel/magento2-weltpixel-newsletter-lite:dev-master
```

Manually:

Important:
Ensure you also install the shared Backend module. If it's already installed, you can skip this. Details in the repo at https://github.com/Weltpixel/magento2-weltpixel-backend.
Ensure you also install the MobileDetect module. If it's already installed, you can skip this. Details in the repo at https://github.com/Weltpixel/magento2-weltpixel-mobiledetect.

Copy the zip into the app/code/WeltPixel/Newsletter directory


#### After installation by either means, enable the extension by running following commands:

```sh
$ php bin/magento module:enable WeltPixel_Newsletter --clear-static-content
$ php bin/magento setup:upgrade
```

### Documentation

For detailed documentation, please visit: https://weltpixel.com/resources/ModuleDoc/Magento2/Newsletter/User-Guide-WeltPixel-Newsletter-Popup-Magento2.html
