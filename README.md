# kashier-cs-cart-plugin
Kashier Cs-cart Plugin

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/kashier-logo.png)
![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/cs-cart.png)

## Supported CS-Cart versions
- - -

- The plugin has been tested with most versions of CS-Cart at every iteration. We recommend using the latest version of CS-Cart, but if that is not possible for some reason, test the plugin with your CS-Cart version and it would probably function properly.

- CS-Cart version last tested on: 4.13.3.

## Features

- Fully PCI DSS compliant as a Level 1 Service for merchant operating in Egypt.

- I-frame integration.

- 3D secure cards authentication support.

- Support multiple payment method.

      1. Card Payments
      2. Wallet Payments 
      3. Bank Installments Payment    

- Support acquiring multiple currencies "EGP, USD, GBP, EUR".

- Plug and play

### Installation

- Download [kashier.zip](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/cs-cart.zip) 

- Log into CS-Cart as administrator.

- Navigate to your CS-Cart admin panel → Addons → Manage Addons→ CS-Cart.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/step-1.png)

- Click on the button shown in the screenshot below then click on `Manual Installation`.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/step-2.png)

- Click on `Local tab` to install your download plugin.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/step-3.png)

- Click on `Upload & Install` to upload your plugin.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/step-4.png)

- Then click on `Administration` → `Payment Methods`

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/step-5.png)

- Add a new payment method by clicking on the Add button on the top right.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/step-6.png)

- Set the name of your payment method and select Kashier from the list. Also Select kashier.tpl for the template.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/step-7.png)

- Navigate to the Configure tab.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/step-8.png)

- Enter your Kashier [Merchant_ID] and [Payment_API_Key] and click Save. These API Keys can be generated from the [Dashboard](https://merchant.kashier.io/en/integrations).

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/step-9.png)


## Obtain Test Credentials

- Login or Sign up on kashier.io https://merchant.kashier.io/

- Navigate to Integrate now section > payment api keys.

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

- Copy Merchant ID visible under your user name "MID-xx-xx".

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/apikey_mid_test.png)

- Insert the MID and Test Api Key in the Configuration page of the Payment Method.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/step-10.png)

- choose payment methods from kashier method list which you would like to use to accept payment via kashier.

- Make sure the test mode is on.

- Save configuration.


## Go live

- After activating your account.

- Make sure you are on live mode.

- Navigate to Integrate now section > payment api keys.

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/apikey_mid_live.png)

- Insert Live Api Key in the Configuration page of each Payment Method.

- Remove the test mode check.

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-cs-cart-plugin/main/steps/step-11.png)


## Support

- Leave us an inquiry ticket on https://kashier.io for questions.
