# Kelkoo Group Sales Tracking Tag Google Tag Manager Template

This tag template makes it easy for merchants to add Kelkoo Group Sales Tracking Tag to Google Tag Manager container. This template is now available through Google's [Community Template Gallery](https://tagmanager.google.com/gallery/). If you have any questions or need any assistance with using this template, please contact your Account Manager.

### Contents: 
* [Before setting up your tag](#preparation)
* [Configuring your tag](#config)
* [Test](#test)

----

## <a name="preparation"></a>Before setting up your Kelkoo Group Sales Tracking Tag

Make sure you have a **Merchant Id** and **Country code** that you can find on the "sales tracking" page of your [Kelkoo Group Merchant Extranet](https://merchant.kelkoogroup.com/).

## <a name="config"></a>Configuring your tag

1. On the `Templates` tab, click on the button `Search Gallery` of the block `Tag Templates` 
1. Search for the Kelkoo Group Sales Tracking Tag, select it, and in the `Template Details` click to the button `Add to workspace`
1. Add a new tag, search for the Kelkoo Group Sales Tracking Tag custom template and select it
1. Configure the variables (country, merchantId, orderId, orderValue)
1. Select the "all page view" trigger for the tag
1. Save the tag


## <a name="test"></a>Test your integration

To test your implementation, simply simulate an order placed on your site.

    Go on your Kelkoo Merchant Extranet and log into your account then click on the link “View your Kelkoo store page” in the top right corner of the Home page
    Click on one of your offers to be redirected to your website
    Place an order on your website
    Save the source code of the confirmation page (as it appears if you do “View” -> “View source”) in case further debugging will be needed
    The next day go on your Kelkoo Merchant Extranet and log into your account
    Check in the “Statistics” menu that the sale has been recorded
    Check that all details have been correctly recorded

Important! Check regularly that sales are being registered. This is extra important to do after you have implemented updates or changes to your site.
If you encounter problems, please use our contact form to send us an email. If the test order was not properly registered in your Statistics page, please attach to your email the source code of the order confirmation page as it appeared (“View”> “View Source”). Kelkoo Sales Tracking code should normally be included.

