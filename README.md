## Semantics3 Push Notifications and Zapier Integration

This is a guide to integrating Semantics3 Push Notifications with Zapier to get price 
change/drop/increase notifications via your favourite channel (Facebook/Gmail/Twitter).

Once you complete the setup of this one-time Zapier integration, you will be able add more products to track thorough your [Semantics3 dashboard](https://semantics3.com/dashboard/playground)


## 1. [Zapier](https://zapier.com)

Zapier connects Semantics3 Push Notifications with 270+ web services. When you ask us if you can
integrate a webapp with Semantics3 Push Notifications, Zapier allows us to say yes a whole lot more.

Zapier uses triggers/actions to automate work between our Push Notifications and other apps. A trigger is an
event that happens in one app and an action is the event that Zapier automatically performs in
another app.

An easy example? Send me an SMS (action) when there is a price drop of a product in your wish list (trigger). The SMS
is the action that Zapier automatically does for you and the price drop event from Semantics3 Push
Notification is what triggers the action to happen.

### 2. Available Semantics3 Push Notifications Triggers

#### Supported Triggers

*	**Price change**: Price of a particular product changes

*	**Price decrease**: Price of a particular product decreases

*	**Price increase**: Price of a particular product increases

Visit this page again soon for whole new range of triggers and possibilities

### 3. What are the most popular Zaps for Semantics3 Push Notifications

*	If you are a consumer, track when price of a product goes below your max budget

*	If you are ecommerce store owner, track price changes of your competitor and get
	the notification through 270+ services.

### 4. How do you setup a Semantics3 Push Notifications Zap

#### 4.1 Create a zap

* **Step 1**: Visit the [Zapier Dashboard](https://zapier.com/app/dashboard) and click on **Make a Zap** button

	![Make a Zap](/zapier_how_to/01_make_a_zap.png)

* **Step 2**: Search and choose **Semantics3 Price Change**

	![Choose trigger](/zapier_how_to/02_choose_trigger.png)

* **Step 3**: Select **Semantics3 Push Notifications account**

	![Select Semantics3 Push Notifications account](/zapier_how_to/03_select_semantics3_account.png)

	a. Visit [semantics3 dashboard](https://www-dashboard.semantics3.com/p#/webhooks)

	b. Click *Add URI* button paste the zapier URL there.

	c. Click *Add Event* button of the zapier URL and provide a product URL you wish to track

* **Step 4**: Select your **action service**. Then hit continue.

	![Select Action Service](/zapier_how_to/04_select_action_service.png)

* **Step 5**: Create Filters. **This step is optional**, you could add filters by eventID to get notified only on
  a particular product among all products you have registered with Semantics3 Push Notifications
  system. Hit continue after this.

* **Step 6**: **Map the Trigger to Action**

  This is where you are able to decide what the action will look like. You can type both static
  text as well as dynamic fields from the trigger service by clicking the "Insert Fields" button in
  the right of each field
  
  Fields inserted from the trigger service show up as little orange pills like so.
  
  This step depends on the action service that you have chosen. For gmail, typically you could just
  fill the following:
  
  - To
  - Subject
  - Plain Body
  
  Hit continue.

* **Step 7**: **Test this Zap**

  This is where you could test if this zap is working. By loading samples, Zapier will pull in the
  most recent trigger items (in our case, a sample Semantics3 Push Notification) and let you test
  the action to see what it looks like. 
  
  Click on **Test Semantics3 Price Change Notifications trigger**
  
  	![Test Semantics3 Price Change Notifications trigger](/zapier_how_to/06_test_this_zap.png)
  
  In the pop-up dialog, copy the zapier hook URL
  
  	![Copy hook URL](/zapier_how_to/07_copy_hook_url.png)
  
  Visit [semantics3 webhooks dashboard](https://www-dashboard.semantics3.com/p#/webhooks) and 
  perform a test trigger. Then come back to the zapier pop-up dialog and click **Ok, I did this**
  
  	![Test Semantics3 Trigger](/zapier_how_to/08_test_trigger_sem3.png)

* **Step 8**: **Name your zap** and Turn On

  The last step is to name your zap and turn it on.
  
  Thats it, you will start receiving price change notifications of products in your wish list.
  
  If you want to add more products to track or stop tracking a product, just go back to
  [Semantics3 Webhooks Dashboard](https://www-dashboard.semantics3.com/p#/webhooks) and add
  or remove the corresponding events.

