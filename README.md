# Hyvä Customer Profile

**Hyvä Customer Profile is a part of MageINIC Customer Profile extension that adds Hyvä features.** This extension extends Customer Profile definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/hyva-customer-profile

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Customer Profile requires installing [MageINIC Customer Profile](https://github.com/mageinic/customer-profile) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/customer-profile
```

## 2. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
