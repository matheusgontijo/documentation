:oro_documentation_types: OroCRM, OroCommerce
:oro_show_local_toc: false

.. _user-guide-dotmailer-overview:
.. _user-guide-dm-integration:

dotmailer Integration
=====================

.. begin_include

Oro application supports out-of-the-box integration with dotmailer, allowing you to do the following:

- Map the :ref:`marketing lists <user-guide-marketing-lists>` to address books in dotmailer and keep them synchronized.
- Use your address books to create email campaigns in dotmailer and import them to Oro application.
- Create new contact data fields to capture additional information about your contacts.
- Use dotmailer campaign statistics and Oro application reporting tools to analyze the campaign efficiency.

Before you can use dotmailer with Oro application, ensure that all the necessary integration steps are complete:

* Configure dotmailer for integration --- please refer to the :ref:`dotmailer Configuration guide <user-guide-dotmailer-configuration>`.
* Check the :ref:`dotmailer Data Fields and Mappings <user-guide-dotmailer-data-fields>` to the Oro application data.
* Set up the schedule for data synchronization between dotmailer and Oro application --- see :ref:`dotmailer Synchronization Settings <admin-configuration-dotmailer-integration-settings>`.
* Optionally, configure dotmailer single sign on --- please follow the :ref:`dotmailer Single Sign-on <user-guide-dotmailer-single-sign-on>` steps.

After configuring the integration and data synchronization, you can :ref:`Send Email Campaign via dotmailer guide <user-guide-dotmailer-campaign>`.

.. finish_include

.. hint:: While dotmailer integration comes out of the box, Oro application can be integrated with other third-party
    systems. Please, refer to the :ref:`Integrations <user-guide-integrations>` section to learn more.

Key Points of Reference
-----------------------

- :ref:`Configure dotmailer Integration <user-guide-dotmailer-configuration>`
- :ref:`Configure dotmailer Synchronization Settings <admin-configuration-dotmailer-integration-settings>`
- :ref:`Manage dotmailer Data Fields and Mappings <user-guide-dotmailer-data-fields>`
- :ref:`Configure dotmailer Single Sign-on <user-guide-dotmailer-single-sign-on>`
- :ref:`Send Email Campaigns via dotmailer <user-guide-dotmailer-campaign>`


.. toctree::
   :hidden:
   :maxdepth: 1

   dotmailer-configuration
   dotmailer-single-sign-on
                    