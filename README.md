# Magento 2 için "Item with the same ID “ID” already exists" hatası çözümü

Magento 2 sitenize oluşan "Item with the same ID “ID” already exists" hatasının http://www.rscoder.com/2019/12/magento-2-how-to-resolve-item-with-same.html adresinde yer alan çözümün modülize edilmiş halidir.

# Kurulum
 - Zip içinden çıkan dosyaları `/app/code/Grinet/DuplicateFix` klasörüne yükleyin

( Unix/Linux/MacOSX için ) 
Magento ana klasörünüze girip aşağıdaki komutları çalıştırın :a
```bash
php bin/magento module:enable Grinet_DuplicateFix
php bin/magento setup:upgrade
php bin/magento cache:clean
```

# Composer ile kurulum
```bash
composer require grinet/Grinet_DuplicateFix
php bin/magento module:enable Grinet_DuplicateFix
php bin/magento setup:upgrade
php bin/magento cache:clean
```

# Hata bildirimi

Gördüğünüz hataları info@grinet.com.tr adresimize iletebilirsiniz...

-----------------------------------------------------------------

# "Item with the same ID “ID” already exists" error fix for Magento2

This solution is published by RsCoder at http://www.rscoder.com/2019/12/magento-2-how-to-resolve-item-with-same.html 
We've converted this an extension.

# Installation
 - Copy all files to `/app/code/Grinet/DuplicateFix` directory

( For Unix/Linux/MacOSX ) 
Go to your root folder of your magento site and run these commands :
```bash
php bin/magento module:enable Grinet_DuplicateFix
php bin/magento setup:upgrade
php bin/magento cache:clean
```

# Installation with composer
```bash
composer require grinet/Grinet_DuplicateFix
php bin/magento module:enable Grinet_DuplicateFix
php bin/magento setup:upgrade
php bin/magento cache:clean
```

# Error reporting

Please send errors to info@grinet.com.tr ...
