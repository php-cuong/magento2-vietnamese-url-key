# magento2-vietnamese-url-key
Fix the bugs related to generating URL Key with the Vietnamese language in Magento 2
# Why should you use this extension?
There is a small bug in Magento 2 while generating URL Key with the Vietnamese language.

The product name:
![ScreenShot](https://github.com/php-cuong/magento2-vietnamese-url-key/blob/master/Screenshot/product-name.png)
Magento generates the url key:
![ScreenShot](https://github.com/php-cuong/magento2-vietnamese-url-key/blob/master/Screenshot/url-key-failed.png)

The problem will be resolved after you install my extension success.

The nice URL key.
![ScreenShot](https://github.com/php-cuong/magento2-vietnamese-url-key/blob/master/Screenshot/nice-url-key.png)

# How to install this extension

Under your root folder, run the following command lines:

- composer require php-cuong/magento2-vietnamese-url-key
- php bin/magento setup:upgrade --keep-generated
- php bin/magento cache:flush
