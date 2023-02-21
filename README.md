SpectroCoin Bitcoin Payment Extension
---------------

**MOVED**

Up to date version can be found in [SpectroCoin Repo](https://github.com/SpectroCoin/Drupal-Bitcoin-Payment-Gateway-Module)

---------------

This merchant module integrates [SpectroCoin](https://spectrocoin.com/) Payments with [Drupal Commerce](https://drupal.org/project/commerce) to accept [Bitcoin](https://bitcoin.org) payments.

**INSTALLATION**

1. Download the module to sites/all/modules or sites/all/modules.
2. Install/Enable the module at admin/modules page.
3. Generate private and public keys [Manually]
    1. Private key:
    ```shell
    # generate a 2048-bit RSA private key
    openssl genrsa -out "C:\private" 2048
    ```
    2. Public key:
    ```shell
    # output public key portion in PEM format
    openssl rsa -in "C:\private" -pubout -outform PEM -out "C:\public"
    ```
4. Generate private and public keys [Automatically]
	1. Private key/Public key:
	Go to [SpectroCoin](https://spectrocoin.com/) -> [Project list](https://spectrocoin.com/en/merchant/api/list.html)
	Click on your project  -> Edit Project -> Click on Public key (You will get Automatically generated private key, you can download it. After that and Public key will be generated Automatically.)

**CONFIGURATION**

1. Configure SpectroCoin options in Home/Administration/Store/Configuration/Payment methods.
2. Enter your Merchant Id, Application Id and Private key (Options are part of the reaction rule settings.)

**INFORMATION** 

1. You can contact us e-mail: info@spectrocoin.com.
2. You can contact us by phone: +442037697306.
3. You can contact us on Skype: spectrocoin_merchant.
