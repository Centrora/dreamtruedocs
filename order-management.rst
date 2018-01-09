Members and Orders Management
************************

DreamTrue Membership combines the members and orders management into the same panel to maximally simplify the admin management work. Members and orders are listed in the menu ``Orders``. The table shows the basic information and action buttons for all members and order including active / expired members and confirmed / pending orders. We can manage the existing members/orders information and also manually create new members/orders.

Search Existing Member/Orders
-----------------------------------------------------

At the top of the page, we can see the search/filter functions to search for the users or orders. The filters include the membership plan, membership expiration date, payment method, order status and membership status.

Basic Member/order Information
-----------------------------------------------

For a record, it shows the basic information including the username, membership plan title, order date, price, order status, and member status. As a record is for one order, the same user may have several records in the list for the same membership or different memberships.

Manage Order Details
------------------------------------------------

Click the ``Edit`` button in the **Order** column to view and edit the Order detailed information. Here, we can change the price of the membership and use ``Update Price`` button to update the price change with the payment gateway. Then the payment gateway will charge the new price in the next recurrence. We can also directly refund the order to the user. The API will automatically issue the refund from the payment gateway account and cancel the order.

Back to the order list, we can click the button under the **Recur** column to cancel a confirmed order or confirm a pending order. When a confirmed order is cancelled, the auto recurring payment will stop in the next recurrence, however, the order will not be refund the membership will stay active until the current expiration date.

Manage Members
---------------------------------------------------

There will be a small green check button for the active members. Clicking on the button will give the option to directly deactivate the membership manually. Also, there is the option to manually activate the membership for the inactive members by clicking the red cross button.

For an active member, we can further edit the membership details. Click the edit button in the **Member Status** column to open the editing panel.

Manage User Data
------------------------------------------------

Users information cab be managed through the button in the **User** column. We can edit the user's username, email, name, password. The information is synchronized with the information in the Joomla! database user tables.

Clicking on the button ``Edit Billing Address`` will switch the panel to the billing information management where we can manage and update the user's billing info.

Create New Member from Existing Users
----------------------------------------------------------

If we want to add a new member to a membership from the existing users on the website, we can use the ``New Member`` button. Choose the membership plan and package and then search for the user whom we plan to add. As the member is manually added, we can set the payment method as the off-line payment (bank transfer).

Create New User
-----------------------------------------------------------

We can also add a new user to the website conveniently in the same panel. Click the ``New User`` button and enter the required user data. After the user is created, we can use the ``New member`` button again to add the new user to a subscription plan.
