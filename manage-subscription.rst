Subscription Management
****************************

All membership/subscription plans are managed in the sidebar menu ``Subscription Plans``. We can create the new plan by the ``New`` button, and also edit the existing plans by the editing buttons following each plan.

Basic Information
--------------------------------

When creating a new plan, you need to configure the basic information. For each plan, we must define the title and the price package. Multiple price packages in the same plan are allowed. In the package, we can define the number of licenses with which the user can register the same number of accounts in the same subscription plan, and also the price. Generally, for the simple scenario, we only need one package which offers one license. In the case the front-end user just signup the subscription for his/her own account. The detailed explanation of the fields is as below.

+--------------------------+---------------------------------------------------------------------------------------+
|Field                     |Explanation                                                                            |
+==========================+=======================================================================================+
|Title                     |Title of the subscription plan                                                         |
+--------------------------+---------------------------------------------------------------------------------------+
|Display Name              |The plan name shown on the front-end registration form                                 |
+--------------------------+---------------------------------------------------------------------------------------+
|Publish                   |If the subscription is published                                                       |
+--------------------------+---------------------------------------------------------------------------------------+
|Ordering                  |Defines the ordering of the plan in the front-end subscription list                    |
+--------------------------+---------------------------------------------------------------------------------------+
|Description               |Description of the subscription plan                                                   |
+--------------------------+---------------------------------------------------------------------------------------+
|Currency                  |Currency of subscription plan price                                                    |
+--------------------------+---------------------------------------------------------------------------------------+
|Life Time Membership      |Defines if the membership is a lifetime one                                            |
+--------------------------+---------------------------------------------------------------------------------------+
|Renewal Options           |If the plan is the auto-recurring subscription or one-off payment membership           |
+--------------------------+---------------------------------------------------------------------------------------+
|Offering Trial            |Defines if the subscription has a trial period when it's an auto recurring plan        |
+--------------------------+---------------------------------------------------------------------------------------+
|Recurrence                |The unit of the subscription recurrence period                                         |
+--------------------------+---------------------------------------------------------------------------------------+
|Length                    |The length of each subscription recurrence period                                      |
+--------------------------+---------------------------------------------------------------------------------------+
|Extra License Price       |The price the extra license under the same plan                                        |
+--------------------------+---------------------------------------------------------------------------------------+
|Add Package               |At least a package is required to define the number of licenses and price of the plan  |
+--------------------------+---------------------------------------------------------------------------------------+
|Package #x                |Different price options defining different license numbers and prices                  |
+--------------------------+---------------------------------------------------------------------------------------+

Email Hook
---------------------------------------

After a plan is created, we can further configure its settings. We can define the email templates which are used for this specific subscription plan. Click the ``Email Hook`` button in the **Hook** column. There, we can specific the email template to use for each even. The email templates need to be configured in advance in the global :ref:`email-settings`.

Affiliate Commissions
-------------------------------------

