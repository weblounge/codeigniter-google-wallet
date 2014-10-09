codeigniter-google-wallet
=========================

********Codeigniter Google Wallet Library********

A PHP implementation of google wallet Digital Goods 
---------------------------------------------------------------------------------------------------------------

Requirements:
---------------------------------------------------------------------------------------------------------------
1. Install apache HTTP Server
2. Install PHP5 or above.


Steps to run this sample application
---------------------------------------------------------------------------------------------------------------

1. Make sure "allow_url_include" option is enabled in php.ini file.

2. Copy the files to default DocumentRoot of the server.

3. Sign up for google wallet ditigal goods at

    Sandbox : https://sandbox.google.com/checkout/customer/gadget/inapp/developersignup.html
    Production : https://checkout.google.com/customer/gadget/inapp/developersignup.html
    
    And get seller Id and seller secret Id.
    
4.  Open application/config/google_wallet.php file and replace $issuerId and $secretKey with your account Ids.

5. You can now visit http://localhost/google_wallet/index.php/pay_with_google in your browser to see the application in action.
