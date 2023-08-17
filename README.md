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

>
# **ÜCRETSİZ Modüllerimiz**
### [Grinet TurkeyCities - Magento2 Türkiye Şehirleri Modülü](https://github.com/grinet/Magento2_TurkeyCities)
### [Grinet TurkeyTaxes - Magento2 Türkiye Vergileri Modülü](https://github.com/grinet/Magento2_TurkeyTaxes)
### [Grinet TCMB Döviz - Magento2 Döviz Kuru Modülü](https://github.com/grinet/Magento2_TCMB_Doviz)
### [Grinet RomCity Import - Magento2 RomCity Şehir Import Modülü](https://github.com/grinet/Magento2_RomcityImportTurkeyCities)
### [Grinet DuplicateFix - Magento2 Hata Fix](https://github.com/grinet/Magento2-DuplicateFix)

>
# **Magento2 Modüllerimiz**

### [Grinet Iyzico - Magento Sanal Pos Modülü](https://magesanalpos.com/grinet-iyzico-magento-icin-sanal-pos-modulu-magento2)
### [Grinet Turkpay2 - Magento2 Banka Sanal Pos Modülü](https://magesanalpos.com/grinet-turkpay-magento-icin-sanal-pos-modulu-magento2)
### [Grinet Kargo - Magento2 Kargo Entegrasyon Modülü](https://magesanalpos.com/grinet-kargo-entegrasyon-modulu-magento-2)

>
# **Magento1 Modüllerimiz**

### [Grinet Iyzico - Magento1 Iyzico Sanal Pos Modülü](https://magesanalpos.com/grinet-iyzico-magento-icin-sanal-pos-modulu-magento1)
### [Grinet Turkpay - Magento1 Banka Sanal Pos Modülü](https://magesanalpos.com/grinet-turkpay-magento-icin-sanal-pos-modulu)
### [Grinet Turkpay Pro - Magento1 Banka Sanal Pos ve Açıktan Tahsilat Modülü](https://magesanalpos.com/grinet-turkpay-magento-icin-sanal-pos-modulu-pro)

