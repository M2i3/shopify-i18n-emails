shopify-i18n-emails
===================

Default Shopify emails in multiple languages. When you are tired of re-inventing the wheels and work in part of the world where English is not the main language. The original english emails are from Shopify. 

How this project is organized
-----------------------------

The default folder contains the original texts in English from Shopify themselves. Each folder contains the template for the 11 email notifications. 

Each template has two files, one with the extension .html (the html version of the email) and one with the extension .txt (the text version of the email). The subject of the email is placed in the .txt file as the first line with the prefix "Subject:"

| File                            | Template                         | Description                                                              |
|---------------------------------|----------------------------------|--------------------------------------------------------------------------|
| abandoned-checkout-notification | Abandoned Checkout Notification  | Sent to a potential customer who has abandoned their checkout            |
| contact-buyer                   | Contact Buyer                    | Used as a default template for 'Email Buyer' emails                      |
| fulfillment-request             | Fulfillment Request              | Sent to custom fulfillment provider when storeowner fulfills order items |
| gift-card-notification          | Gift Card Notification           | Sent to the customer when a gift card is created                         |
| new-order-notification          | New Order Notification           | Sent to all subscribers of Order Confirmation Notifications              |
| new-order-notification-mobile   |  New Order Notification (mobile) | Sent to all subscribers of Order Confirmation Notifications for mobile   |
| order-cancelled                 | Order Cancelled                  | Sent to the customer when an order is cancelled                          |
| order-confirmation              | Order Confirmation               | Sent to the customer when an order is created                            |
| pos-and-mobile-receipt          | POS and Mobile Receipt           | Sent to customer through point of sale and mobile                        |
| refund-notification             | Refund Notification              | Sent to the customer when their order is refunded                        |
| Shipping confirmation           | Shipping confirmation            | Sent to the customer when an order is shipped                            |
| Shipping update                 | Shipping update                  | Sent to the customer when an order's shipping information is updated     |


How to submit your translations
-------------------------------

Translations are more than welcome. To add new translations please fork this project and submit a Pull Request. 
Small typo corrections can also be handled through the Issues (but remember we are as busy as you are and they might not get done right away).


Please follow the IETF language tag when adding languages this project. We don't want to start a battle to see if it should be a Z or a S.



