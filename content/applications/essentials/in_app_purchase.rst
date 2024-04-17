<<<<<<< HEAD
=====================
In-app purchase (IAP)
=====================
||||||| parent of e7edef6ec (temp)
=====================
In-App Purchase (IAP)
=====================
=======
======================
In-app purchases (IAP)
======================
>>>>>>> e7edef6ec (temp)

<<<<<<< HEAD
.. |IAP| replace:: :abbr:`IAP (In-app purchases)`

In-app purchases (IAP) are optional services that enhance Odoo databases. Each service provides its
own specific features and functionality. A full list of services is available on the `Odoo IAP
Catalog <https://iap.odoo.com/iap/all-in-app-services>`_.

.. image:: in_app_purchase/iap.png
   :align: center
   :alt: The IAP catalog with various services available on IAP.Odoo.com.

.. example::
   The :guilabel:`SMS` service sends text messages to contacts directly from the database, and the
   :guilabel:`Documents Digitization` service digitizes scanned or PDF vendor bills, expenses, and
   resumes with optical character recognition (OCR) and artificial intelligence (AI).

|IAP| services do **not** need to be configured or set up before use. Odoo users can simply click on
the service in the app to activate it. However, each service requires its own prepaid credits, and
when they run out, users **must** :ref:`buy more <iap/buying_credits>` in order to keep using it.

.. note::
   Users with an Enterprise version of Odoo Online get free credits to test IAP features.

.. _in_app_purchase/portal:

IAP services
============

|IAP| services are provided by Odoo, as well as third-parties, and have a wide range of uses.

The following |IAP| services are provided by Odoo:

- :guilabel:`Documents Digitization`: digitizes scanned or PDF vendor bills, expenses, and resumes
  with OCR and AI.
- :guilabel:`Partner Autocomplete`: automatically populates contact records with corporate data.
- :guilabel:`SMS`: sends SMS text messages to contacts directly from the database.
- :guilabel:`Lead Generation`: generates leads based on a set of criteria, and converts web visitors
  into quality leads and opportunities.
- :guilabel:`Snailmail`: sends customer invoices and follow-up reports by post, worldwide.

For more information on every service currently available, visit the `Odoo IAP Catalog
<https://iap.odoo.com/iap/all-in-app-services>`_.

Use IAP services
----------------

|IAP| services are automatically integrated with Odoo, and do **not** require users to configure any
settings. To use a service, simply interact with it wherever it appears in the database.

.. example::
   The following flow focuses on the *SMS* |IAP| service being used from a contact's record.

   This can be done by clicking the :guilabel:`📱 (phone) SMS` icon within the database.

   .. image:: in_app_purchase/sms-icon.png
      :align: center
      :alt: The SMS icon on a typical contact information form located within an Odoo database.

   One way to utilize the *SMS* |IAP| service with Odoo is showcased in the following steps:

   #. Navigate to the :menuselection:`Contacts application`, and click on a contact with a mobile
      phone number entered in either the :guilabel:`Phone` or :guilabel:`Mobile` field of the
      contact form.
   #. Hover the mouse over the :guilabel:`Phone` or :guilabel:`Mobile` field, and a :guilabel:`📱
      (phone) SMS` icon appears to the right.
   #. Click the :guilabel:`📱 (phone) SMS` icon, and a :guilabel:`Send SMS Text Message` pop-up
      window appears.
   #. Type a message in the :guilabel:`Message` field of the :guilabel:`Send SMS Text Message`
      pop-up window. Then, click the :guilabel:`Send SMS` button. Odoo then sends the message, via
      SMS, to the contact, and logs what was sent in the *chatter* of the contact's form.

   Upon sending the SMS message, the prepaid credits for the *SMS* |IAP| service are automatically
   deducted from the existing credits. If there are not enough credits to send the message, Odoo
   prompts the user to purchase more.

.. seealso::
   For more information on how to use various |IAP| services, and for more in-depth instructions
   related to SMS functionality in Odoo, review the documentation below:

   - :doc:`Lead mining </applications/sales/crm/acquire_leads/lead_mining>`
   - :doc:`Enrich your contacts base with Partner Autocomplete
     </applications/sales/crm/optimize/partner_autocomplete>`
   - :doc:`SMS essentials </applications/marketing/sms_marketing/essentials/sms_essentials>`

.. _in_app_purchase/credits:

IAP credits
===========

Every time an |IAP| service is used, the prepaid credits for that service are spent. Odoo prompts
the purchase of more credits when there are not enough credits left to continue using a service.
Email alerts can also be set up for when :ref:`credits are low <in_app_purchase/low-credits>`.

Credits are purchased in *Packs* from the `Odoo IAP Catalog
<https://iap.odoo.com/iap/all-in-app-services>`_, and pricing is specific to each service.

.. example::
   The `SMS service <https://iap.odoo.com/iap/in-app-services/1>`_ has four packs available, in
   denominations of:

   - :guilabel:`Starter Pack`: 10 credits
   - :guilabel:`Standard Pack`: 100 credits
   - :guilabel:`Advanced Pack`: 500 credits
   - :guilabel:`Expert Pack`: 1,000 credits

   .. image:: in_app_purchase/packs.png
      :align: center
      :alt: Four different packs of credits for the SMS IAP service.

   The number of credits consumed depends on the length of the SMS and the country of destination.

   For more information, refer to the :doc:`SMS Pricing and FAQ
   </applications/marketing/sms_marketing/pricing/pricing_and_faq>` documentation.
||||||| parent of e7edef6ec (temp)
In-App Purchases (IAP) gives access to additional services through Odoo. For instance, it allows you
to send SMS Text Messages or to send Invoices by post directly from your database.
=======
.. |IAP| replace:: :abbr:`IAP (In-app purchases)`

In-app purchases (IAP) are optional services that enhance Odoo databases. Each service provides its
own specific features and functionality. A full list of services is available on the `Odoo IAP
Catalog <https://iap.odoo.com/iap/all-in-app-services>`_.

.. image:: in_app_purchase/iap.png
   :align: center
   :alt: The IAP catalog with various services available on IAP.Odoo.com.

.. example::
   The :guilabel:`SMS` service sends text messages to contacts directly from the database, and the
   :guilabel:`Documents Digitization` service digitizes scanned or PDF vendor bills, expenses, and
   resumes with optical character recognition (OCR) and artificial intelligence (AI).

|IAP| services do **not** need to be configured or set up before use. Odoo users can simply click on
the service in the app to activate it. However, each service requires its own prepaid credits, and
when they run out, users **must** :ref:`buy more <iap/buying_credits>` in order to keep using it.

.. note::
   Enterprise Odoo users with a valid subscription get free credits to test IAP features before
   deciding to purchase more credits for the database. This includes demo/training databases,
   educational databases, and one-app-free databases.

.. _in_app_purchase/portal:

IAP services
============

|IAP| services are provided by Odoo, as well as third-parties, and have a wide range of uses.

The following |IAP| services are offered by Odoo:

- :guilabel:`Documents Digitization`: digitizes scanned or PDF vendor bills, expenses, and resumes
  with OCR and AI.
- :guilabel:`Partner Autocomplete`: automatically populates contact records with corporate data.
- :guilabel:`SMS`: sends SMS text messages to contacts directly from the database.
- :guilabel:`Lead Generation`: generates leads based on a set of criteria, and converts web visitors
  into quality leads and opportunities.
- :guilabel:`Snailmail`: sends customer invoices and follow-up reports by post, worldwide.
- :guilabel:`Signer identification with itsme®️`: ask document signatories in Odoo *Sign* to provide
  their identity using the *itsme®* identity platform, which is available in Belgium and the
  Netherlands.

For more information on every service currently available (offered from developers other than Odoo),
visit the `Odoo IAP Catalog <https://iap.odoo.com/iap/all-in-app-services>`_.

Use IAP services
----------------

|IAP| services are automatically integrated with Odoo, and do **not** require users to configure any
settings. To use a service, simply interact with it wherever it appears in the database.

.. example::
   The following flow focuses on the *SMS* |IAP| service being used from a contact's record.

   This can be done by clicking the :guilabel:`📱 SMS` icon within the database.

   .. image:: in_app_purchase/sms-icon.png
      :align: center
      :alt: The SMS icon on a typical contact information form located within an Odoo database.

   One way to utilize the *SMS* |IAP| service with Odoo is showcased in the following steps:

   First, navigate to the :menuselection:`Contacts application`, and click on a contact with a
   mobile phone number entered in either the :guilabel:`Phone` or :guilabel:`Mobile` field of the
   contact form.

   Next, find the :guilabel:`📱 SMS` icon that appears to the right of the :guilabel:`Phone` or
   :guilabel:`Mobile` fields. Click the :guilabel:`📱 SMS` icon, and a :guilabel:`Send SMS Text
   Message` pop-up window appears.

   Type a message in the :guilabel:`Message` field of the pop-up window. Then, click the
   :guilabel:`Send SMS` button. Odoo then sends the message, via SMS, to the contact, and logs what
   was sent in the *chatter* of the contact's form.

   Upon sending the SMS message, the prepaid credits for the *SMS* |IAP| service are automatically
   deducted from the existing credits. If there are not enough credits to send the message, Odoo
   prompts the user to purchase more.

.. seealso::
   For more information on how to use various |IAP| services, and for more in-depth instructions
   related to SMS functionality in Odoo, review the documentation below:

   - :doc:`Lead mining <../sales/crm/acquire_leads/lead_mining>`
   - :doc:`Enrich your contacts base with Partner Autocomplete
     <../sales/crm/optimize/partner_autocomplete>`
   - :doc:`SMS essentials <../marketing/sms_marketing/essentials/sms_essentials>`

.. _in_app_purchase/credits:

IAP credits
===========

Every time an |IAP| service is used, the prepaid credits for that service are spent. Odoo prompts
the purchase of more credits when there are not enough credits left to continue using a service.
Email alerts can also be set up for when :ref:`credits are low <in_app_purchase/low-credits>`.

Credits are purchased in *Packs* from the `Odoo IAP Catalog
<https://iap.odoo.com/iap/all-in-app-services>`_, and pricing is specific to each service.

.. example::
   The `SMS service <https://iap.odoo.com/iap/in-app-services/1>`_ has four packs available, in
   denominations of:

   - :guilabel:`Starter Pack`: 10 credits
   - :guilabel:`Standard Pack`: 100 credits
   - :guilabel:`Advanced Pack`: 500 credits
   - :guilabel:`Expert Pack`: 1,000 credits

   .. image:: in_app_purchase/packs.png
      :align: center
      :alt: Four different packs of credits for the SMS IAP service.

   The number of credits consumed depends on the length of the SMS and the country of destination.

   For more information, refer to the :doc:`SMS Pricing and FAQ
   <../marketing/sms_marketing/pricing/pricing_and_faq>` documentation.
>>>>>>> e7edef6ec (temp)

.. _iap/buying_credits:

Buy credits
-----------

<<<<<<< HEAD
If there are not enough credits to perform a task, the database automatically prompts the purchase
of more credits.
||||||| parent of e7edef6ec (temp)
Each IAP Service relies on prepaid credits to work and has its own pricing. To consult your current
balance or to recharge your account, go to :menuselection:`Settings --> Odoo IAP --> View my
Services`.
=======
If there are not enough credits to perform a task, the database automatically prompts the purchase
of more credits.

Users can check the current balance of credits for each service, and manually purchase more credits,
by navigating to the :menuselection:`Settings app --> Contacts section`, and beneath the
:guilabel:`Odoo IAP` setting, click :guilabel:`View My Services`.

Doing so reveals a :guilabel:`My Services` page, listing the various |IAP| services in the database.
From here, click an |IAP| service to open its :guilabel:`Account Information` page, where additional
credits can be purchased.

Manually buy credits
~~~~~~~~~~~~~~~~~~~~

To manually buy credits in Odoo, follow these steps:

First, go to the :menuselection:`Settings application` and type `IAP` in the :guilabel:`Search...`
bar. Alternatively users can scroll down to the :guilabel:`Contacts` section. Under the
:guilabel:`Contacts` section, where it says :guilabel:`Odoo IAP`, click :guilabel:`View My
Services`.
>>>>>>> e7edef6ec (temp)

<<<<<<< HEAD
Users can check the current balance of credits for each service, and manually purchase more credits,
by navigating to the :menuselection:`Settings app --> Search IAP --> View My Services`.
||||||| parent of e7edef6ec (temp)
.. image:: in_app_purchase/image1.png
   :align: center
=======
.. image:: in_app_purchase/view-services.png
   :align: center
   :alt: The Settings app showing the Odoo IAP heading and View My Services button.
>>>>>>> e7edef6ec (temp)

<<<<<<< HEAD
Doing so reveals an :guilabel:`IAP Account` page, listing the various |IAP| services in the
database. From here, click an |IAP| service to open its :guilabel:`Account Information` page, where
additional credits can be purchased.
||||||| parent of e7edef6ec (temp)
.. tip::
   If you are on Odoo Online and have the Enterprise version, you benefit from free credits to test our
   IAP features.
=======
Doing so reveals an :guilabel:`IAP Account` page, listing the various |IAP| services in the
database. From here, click an |IAP| service to open details about it; additional credits can be
purchased from here.
>>>>>>> e7edef6ec (temp)

<<<<<<< HEAD
Manually buy credits
~~~~~~~~~~~~~~~~~~~~
||||||| parent of e7edef6ec (temp)
IAP accounts
============
=======
On the following page, click the :guilabel:`Buy Credit` button. Doing so loads a :guilabel:`Buy
Credits for (IAP Account)` page in a new tab. From here, click :guilabel:`Buy` on the desired pack
of credits. Then, follow the prompts to enter payment details, and confirm the order.
>>>>>>> e7edef6ec (temp)

<<<<<<< HEAD
To manually buy credits in Odoo, follow these steps:

#. Go to the :menuselection:`Settings application`.
#. Type `IAP` in the search bar.
#. Click :guilabel:`View My Services`.
||||||| parent of e7edef6ec (temp)
Credits to use IAP services are stored on IAP accounts, which are specific to each service.
By default, IAP accounts are common to all companies, but can be restricted to specific
ones. Activate the :ref:`developer mode <developer-mode>`, then go to :menuselection:`Technical
Settings --> IAP Account`.

.. image:: in_app_purchase/image2.png
   :align: center
=======
.. image:: in_app_purchase/buy-pack.png
   :align: center
   :alt: The SMS service page on IAP.Odoo.com with four packs of credits available for purchase.
>>>>>>> e7edef6ec (temp)

<<<<<<< HEAD
   .. image:: in_app_purchase/view-services.png
      :align: center
      :alt: The Settings app showing the Odoo IAP heading and View My Services button.
||||||| parent of e7edef6ec (temp)
.. tip::
   An IAP account can be disabled by appending `+disabled` to its token.
   Reverting this change will re-enable the account.
=======
Once the transaction is complete, the credits are available for use in the database.
>>>>>>> e7edef6ec (temp)

<<<<<<< HEAD
#. Doing so reveals an :guilabel:`IAP Account` page, listing the various |IAP| services in the
   database. From here, click an |IAP| service to open its :guilabel:`Account Information` page,
   where additional credits can be purchased.
#. On the :guilabel:`Account Information` page, click the :guilabel:`Buy Credit` button.
||||||| parent of e7edef6ec (temp)
IAP Portal
==========
=======
.. _in_app_purchase/low-credits:
>>>>>>> e7edef6ec (temp)

<<<<<<< HEAD
   .. image:: in_app_purchase/account-info.png
      :align: center
      :alt: The Account Information page for an IAP service showing the Buy Credit button.
||||||| parent of e7edef6ec (temp)
The IAP Portal is a platform regrouping your IAP Services. It is accessible from
:menuselection:`Settings app --> Odoo IAP --> View my Services`. From there, you can view your current
balance, recharge your credits and set a reminder when your balance falls below a threshold.
=======
Low-credit notification
~~~~~~~~~~~~~~~~~~~~~~~
>>>>>>> e7edef6ec (temp)

<<<<<<< HEAD
#. Doing so loads a :guilabel:`Buy Credits for (IAP Account)` page in a new tab. From here, click
   :guilabel:`Buy` on the desired pack of credits. Then, follow the prompts to enter payment
   details, and confirm the order.
||||||| parent of e7edef6ec (temp)
.. image:: in_app_purchase/image3.png
   :align: center
=======
It is possible to be notified when credits are low, in order to avoid running out of credits, while
using an |IAP| service. To do that, follow this process:
>>>>>>> e7edef6ec (temp)

<<<<<<< HEAD
   .. image:: in_app_purchase/buy-pack.png
      :align: center
      :alt: The SMS service page on IAP.Odoo.com with four packs of credits available for purchase.
||||||| parent of e7edef6ec (temp)
Get notified when credits are low
=================================
=======
Go to the :menuselection:`Settings application`, and type `IAP` in the :guilabel:`Search...` bar.
Under the :guilabel:`Contacts` section, where it says :guilabel:`Odoo IAP`, click :guilabel:`View My
Services`.
>>>>>>> e7edef6ec (temp)

<<<<<<< HEAD
#. Once the transaction is complete, the credits are available for use in the database.
||||||| parent of e7edef6ec (temp)
To be notified when it’s time to recharge your credits, you can go to your IAP Portal through
:menuselection:`Settings app --> Odoo IAP --> View my Services`, unfold a service and check the
Receive threshold warning option. Then, you can provide a minimum amount of credits and email
addresses. Now, every time that the limit is reached, an automatic reminder will be sent by
email!
=======
The available |IAP| accounts appear in a list view on the :guilabel:`IAP Account` page. From here,
click on the desired |IAP| account to view that service's details.
>>>>>>> e7edef6ec (temp)

<<<<<<< HEAD
.. _in_app_purchase/low-credits:

Low-credit notification
~~~~~~~~~~~~~~~~~~~~~~~

It is possible to be notified when credits are low, in order to avoid running out of credits, while
using an |IAP| service. To do that, follow this process:

#. Go to the :menuselection:`Settings application`.
#. Type `IAP` in the search bar.
#. Click :guilabel:`View My Services`.
#. The available |IAP| accounts appear in a list view on the :guilabel:`IAP Account` page. From
   here, click on the desired |IAP| account to view that service's :guilabel:`Account Information`
   page.
#. On the :guilabel:`Account Information` page, tick the :guilabel:`Warn Me` box. Doing so reveals
   two fields on the form: :guilabel:`Threshold` and :guilabel:`Warning Email`.

   .. image:: in_app_purchase/low-credits.png
      :align: center
      :alt: Odoo will send an email alert when credits for this service fall below the threshold.

#. In the :guilabel:`Threshold` field, enter an amount of credits Odoo should use as the minimum
   threshold for this service.
#. In the :guilabel:`Warning Email` field, enter the email address that should receive the
   notification.

Odoo sends a low-credit alert to the :guilabel:`Warning Email` when the balance of credits falls
below the amount listed as the :guilabel:`Threshold`.
||||||| parent of e7edef6ec (temp)
.. image:: in_app_purchase/image4.png
   :align: center
=======
On the details page, tick the :guilabel:`Receive threshold warning` checkbox. Doing so reveals two
fields on the form: :guilabel:`Warning Threshold` and :guilabel:`Contact Email`.

In the :guilabel:`Warning Threshold` field, enter an amount of credits Odoo should use as the
minimum threshold for this service. In the :guilabel:`Contact Email` field, enter the email address
that receives the notification.

Odoo sends a low-credit alert to the :guilabel:`Contact Email` when the balance of credits falls
below the amount listed as the :guilabel:`Warning Threshold`.
>>>>>>> e7edef6ec (temp)
