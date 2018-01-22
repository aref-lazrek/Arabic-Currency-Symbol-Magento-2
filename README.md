# Show-Arabic-Currency-Symbol-Magento-2
A simple module to solve magento 2 issue with Arabic currency symbol not displaying


Installation - Installing using archive

Download ZIP Archive
Put extracted files in app folder of your Magento 2 root directory : app/code/Aref/ArabicCurrency

If your not in developer mode you need to run these commands:

php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento cache:clean


These is a known issue in magento2 and I've submitted it to magento repo 
https://github.com/magento/magento2/issues/13207
