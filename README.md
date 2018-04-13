Magento 2 German (Switzerland) Language Pack
=============

Facts
-----
- Based on [Magento2_German_LocalePack_de_DE](https://github.com/splendidinternet/Magento2_German_LocalePack_de_DE) from Splendid Internet GmbH & Co. KG
- Adaptions for the Swiss-German language ("Kanton" instead of "Bundesland", "ss" instead of "ß")

Requirements
------------
- PHP  5.6 / 7.0

Installation
------------
```bash
composer require chuvisco88/magento2-language-pack-de-ch
rm pub/static/frontend/Magento/luma/de_DE/js-translation.json
php bin/magento setup:static-content:deploy de_CH
```

Compatibility
-------------
- Magento >= 2.0

Support
-------
If you have any issues with this extension, open an issue on [GitHub](https://github.com/chuvisco88/magento2-language-pack-de-ch/issues).

Contribution
------------
Any contribution is highly appreciated. The best way to contribute code is to open a [pull request on GitHub](https://help.github.com/articles/using-pull-requests).

Developer
---------
Fabian Schweizer and maybe some [contributors](https://github.com/chuvisco88/magento2-language-pack-de-ch/contributors) in future

License
-------
[Open Software License ("OSL") v. 3.0](https://opensource.org/licenses/OSL-3.0)

Copyright
---------
(c) 2018, Fabian Schweizer
