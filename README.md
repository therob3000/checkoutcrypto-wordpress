CheckoutCrypto Wordpress Client (wp_cc)
==========
A payment option for the WP E-commerce shopping cart for Wordpress.

Features
==========
* Automatically generate payment address to customer on site at checkout and via email.
Prerequisites

Prerequisites
==========

* Wordpress
* WP eCommerce plugin  https://wordpress.org/plugins/wp-e-commerce/
* cURL support

* An account with checkoutcrypto.com  registration is free, all deposits and withdraws are charged a fee.

* Preferred coins must be enabled from your account on checkoutcrypto.com


INSTALL
==========

1. install wp-e-commerce

2. copy contents of wp-e-commerce to plugins/wp-e-commerce/   

3. set permissions 

   sudo chmod 777 ./wp-content/wp-e-commerce/wpsc-merchants/checkoutcrypto -R

	Coin Image Storage permissions

   sudo chmod 777 ./wp-content/uploads/checkoutcrypto -R

3. activate checkoutcrypto plugin. (seperate from payment module)

4. activate checkoutcrypt payment module in wp-e-commerce plugin. Go to Settings->Store->checkoutCrypto -> API. 

5. Copy and paste your API key from your CheckoutCrypto.com Account, into your CheckoutCrypto Payment Module in step 4.

6. Press "refresh coins", to add all inital coins or refresh all coin rates. If you add a new coin, in order to cache the rate, coin, image, empty the MySQL $wp_prefix.cc_coins table manually, then back in the Payment Menu, hit "refresh coins" again.


Support
==========

Email
info@checkoutcrypto.com

Submit a ticket to our support, using your checkoutcrypto.com account.
