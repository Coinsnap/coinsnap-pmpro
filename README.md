# Coinsnap for Paid Memberships Pro payment plugin #
![Coinsnap for Paid meberships pro](https://github.com/Coinsnap/Coinsnap-for-PaidMembershipsPro/blob/main/assets/images/1.png)

## Bitcoin and Lightning payments for Paid Memberships Pro in WordPress ##

* Contributors: coinsnap
* Tags: Lightning, Lightning Payment, SATS, Satoshi sats, bitcoin, Wordpress, Paid Memberships Pro, paywall, payment gateway, accept bitcoin, bitcoin plugin, bitcoin payment processor, bitcoin e-commerce, Lightning Network, cryptocurrency, lightning payment processor
* Requires PHP: 7.4
* Tested up to: 6.6.2
* Stable tag: 1.0.0
* License: GPL2
* License URI: https://www.gnu.org/licenses/gpl-2.0.html

Bitcoin and Lightning payment processing with the Coinsnap add-on for PaidMembershipsPro Wordpress Plug-in.

* Paid Memberships Pro Demo Donation Page: https://paidmembershippro.coinsnap.org/
* Blog Article: https://coinsnap.io/en/coinsnap-for-paid-memberships-pro-payment-plugin/
* WordPress: https://wordpress.org/plugins/coinsnap-for-paidmembershipspro/
* GitHub: https://github.com/Coinsnap/Coinsnap-for-PaidMembershipsPro

* Description *

[Coinsnap](https://coinsnap.io/en/) for Paid Memberships Pro allows you to process Bitcoin Lightning payments over the Lightning network. 
With the Coinsnap Bitcoin-Lightning payment plugin for Paid Memberships Pro you only need a Lightning wallet with a Lightning address to accept Bitcoin Lightning payments on your Wordpress site.

Coinsnap’s payment plugin for Paid Memberships Pro makes it amazingly simple for your customers to purchase your offerings with Bitcoin-Lightning: They can make their transactions with just a scan of the QR code generated by the Coinsnap plugin, and the authorization of the payment. 
When authorized, the payment will be credited to your Lightning wallet in real time. 

* Bitcoin and Lightning payments in Paid Memberships Pro with Coinsnap *

![Paid Memberships Pro](https://github.com/Coinsnap/Coinsnap-for-PaidMembershipsPro/blob/main/assets/images/12.png)

If you sell restricted content and manage membership subscriptions with recurring payments based on Paid Memberships Pro for WordPress, then you can easily integrate payment processing via Bitcoin and Lightning with the Coinsnap plugin.

With the Coinsnap Bitcoin Lightning payment processing plugin you can immediately accept Bitcoin Lightning payments on your site. You don’t need your own Lightning node or any other technical requirements - just install the Coinsnap for Paid Memberships Pro plugin.

Simply register on [Coinsnap](https://app.coinsnap.io/register), enter your own Lightning address and install the Coinsnap payment module in your wordpress backend. Add your store ID and your API key which you’ll find in your Coinsnap account, and your customers can pay you with Bitcoin Lightning right away!

* Features: *

* **All you need is a Lightning Wallet with a Lightning address. [Here you can find an overview of the matching Lightning Wallets](https://coinsnap.io/en/lightning-wallet-with-lightning-address/)**

* **Accept Bitcoin and Lightning payments** in your online store **without running your own technical infrastructure.** You do not need your own server, nor do you need to run your own Lightning Node.

* **Quick and easy registration at Coinsnap**: Just enter your email address and your Lightning address – and you are ready to integrate the payment module and start selling for Bitcoin Lightning. You will find the necessary IDs and Keys here, too.

* **100% protected privacy**:
    * We do not collect personal data.
    * For the registration you only need an e-mail address, which we will also use to inform you when we have received a payment.
    * No other personal information is required as long as you request a withdrawal to a Lightning address or Bitcoin address.

* **Only 1 % fees!**:
    * No basic fee, no transaction fee, only 1% on the invoice amount with referrer code.
    * Without referrer code the fee is 1.25%.
    * Get a referrer code from our partners and customers and save 0.25% fee.

* **No KYC needed**:
    * Direct, P2P payments (instantly to your Lightning wallet)
    * No intermediaries and paperwork
    * Transaction information is only shared between you and your customer

* **Sophisticated merchant’s admin dashboard in Coinsnap:**:
    * See all your transactions at a glance
    * Follow-up on individual payments
    * See issues with payments
    * Export reports

* **A Bitcoin payment via Lightning offers significant advantages**:
    * Lightning **payments are executed immediately.**
    * Lightning **payments are credited directly to the recipient.**
    * Lightning **payments are inexpensive.**
    * Lightning **payments are guaranteed.** No chargeback risk for the merchant.
    * Lightning **payments can be used worldwide.**
    * Lightning **payments are perfect for micropayments.**

* **Multilingual interface and support**: We speak your language

* Documentation: *

* [Coinsnap API (1.0) documentation](https://docs.coinsnap.io/)
* [Frequently Asked Questions](https://coinsnap.io/en/faq/) 
* [Terms and Conditions](https://coinsnap.io/en/general-terms-and-conditions/)
* [Privacy Policy](https://coinsnap.io/en/privacy/)


# Installation #

### 1. Install the Coinsnap PaidMembershipsPro plug-in from the WordPress directory. ###

The Coinsnap PaidMembershipsPro plug-in can be searched and installed in the WordPress plugin directory.

In your WordPress instance, go to the Plugins > Add New section.
In the search you enter Coinsnap and get as a result the Coinsnap PaidMembershipsPro plug-in displayed.

Then click Install.

After successful installation, click Activate and then you can start setting up the plugin.

### 1.1. Add plugin ###

![Plugin downloading from Github repository](https://github.com/Coinsnap/Coinsnap-for-PaidMembershipsPro/blob/main/assets/images/2.jpg)

If you don’t want to install add-on directly via plugin, you can download Coinsnap PaidMembershipsPro plug-in from Coinsnap Github page or from WordPress directory and install it via “Upload Plugin” function:

Navigate to Plugins > Add Plugins > Upload Plugin and Select zip-archive downloaded from Github.

![Manual plugin installation](https://github.com/Coinsnap/Coinsnap-for-PaidMembershipsPro/blob/main/assets/images/3.png)

Click “Install now” and Coinsnap PaidMembershipsPro plug-in will be installed in WordPress.

After you have successfully installed the plugin, you can proceed with the connection to Coinsnap payment gateway.

### 1.2. Configure Coinsnap PaidMembershipsPro plug-in ###

![Plugins list](https://github.com/Coinsnap/Coinsnap-for-PaidMembershipsPro/blob/main/assets/images/4.png)

After the Coinsnap PaidMembershipsPro plug-in is installed and activated, a notice appears that the plugin still needs to be configured.

### 1.3. Deposit Coinsnap data ###

![Plugin settings](https://github.com/Coinsnap/Coinsnap-for-PaidMembershipsPro/blob/main/assets/images/5.png)

* Navigate to Memberships > Settings > Payment Gateway and select coinsnap
* Enter Store ID and API Key
* Click Save Setting

![Coinsnap store settings](https://github.com/Coinsnap/Coinsnap-for-PaidMembershipsPro/blob/main/assets/images/6.png)

#### Enter Shop-ID ####
Retrieve the store ID from the previously copied information within the Coinsnap app. Enter this information in the first field provided.

#### Enter API key ####
Get the API key from the information previously copied into the Coinsnap app. Enter this information in the second field provided. Make sure to synchronise the invoice statuses for “Expired”, “Billed” and “In Progress” to maintain accurate and up-to-date records.

![Currency and tax settings](https://github.com/Coinsnap/Coinsnap-for-PaidMembershipsPro/blob/main/assets/images/7.png)

#### (1) Currency and tax configuration #### 
Select the desired currency from the available list. Please note that Coinsnap does currently support the following currencies: “EUR”, “USD”, “CAD”, “JPY”, “GBP” and “CHF”.

#### (2) Confirm the changes ####
To apply and save all changes, click on the blue button at the end of the process.

If you don’t have a Coinsnap account yet, you can do so via the link shown: Coinsnap Registration

### 2. Create Coinsnap account ####

![Coinsnap register](https://github.com/Coinsnap/Coinsnap-for-PaidMembershipsPro/blob/main/assets/images/8.png)

### 2.1. Create a Coinsnap Account ####

Now go to the Coinsnap website at: https://app.coinsnap.io/register and open an account by entering your email address and a password of your choice.

If you are using a Lightning Wallet with Lightning Login, then you can also open a Coinsnap account with it.

### 2.2. Confirm email address ####

![E-mail address confirmation](https://github.com/Coinsnap/Coinsnap-for-PaidMembershipsPro/blob/main/assets/images/9.png)

You will receive an email to the given email address with a confirmation link, which you have to confirm. If you do not find the email, please check your spam folder.

Then please log in to the Coinsnap backend with the appropriate credentials.

### 2.3. Set up website at Coinsnap ###

After you sign up, you will be asked to provide two pieces of information.

In the Website Name field, enter the name of your online store that you want customers to see when they check out.

In the Lightning Address field, enter the Lightning address to which the Bitcoin and Lightning transactions should be forwarded.

A Lightning address is similar to an e-mail address. Lightning payments are forwarded to this Lightning address and paid out. If you don’t have a Lightning address yet, set up a Lightning wallet that will provide you with a Lightning address.

![Connect website with Coinsnap](https://github.com/Coinsnap/Coinsnap-for-PaidMembershipsPro/blob/main/assets/images/10.png)

For more information on Lightning addresses and the corresponding Lightning wallet providers, click here:
https://coinsnap.io/lightning-wallet-mit-lightning-adresse/

### 3. Connect Coinsnap account with PaidMembershipsPro plug-in ###

### 3.1. PaidMembershipsPro Coinsnap Settings ###

* Navigate to Memberships > Settings > Payment Gateway and select coinsnap
* Enter Store ID and API Key
* Click Save Setting

### 4. Test payment ###

### 4.1. Test payment in PaidMembershipsPro ###

After all the settings have been made, a test payment should be made.

We make a real donation payment in our test PaidMembershipsPro site.

### 4.2. Bitcoin + Lightning payment page ###

The Bitcoin + Lightning payment page is now displayed, offering the payer the option to pay with Bitcoin or also with Lightning. Both methods are integrated in the displayed QR code.

![QR code on the Bitcoin payment page](https://github.com/Coinsnap/Coinsnap-for-PaidMembershipsPro/blob/main/assets/images/11.png)
