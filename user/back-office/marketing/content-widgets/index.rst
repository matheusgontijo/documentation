:oro_documentation_types: OroCommerce

.. _user-guide--landing-pages--marketing--content-widgets:
.. _content-widgets-user-guide:

Content Widgets
===============

Content widgets are snippets of structured information that you can insert into any WYSIWYG field in your application. WYSIWYG fields are available throughout OroCommerce; for example, on edit pages of products, content blocks, and landing pages.

There are three content widget types:

* An Image Slider
* A Contact Us form
* A Copyright

Each of these widget types has a different set of options.

Please keep in mind that:

+---------------------------------------------------------------------+
|You can:                                                             |
|                                                                     |
|* Edit content widgets from the grid and view page.                  |
|                                                                     |
|You cannot:                                                          |
|                                                                     |
|* Delete a widget if it is used in a content block or a landing page.|
|* Change widget type for an already existing widget                  |
+---------------------------------------------------------------------+

Create a Content Widget
-----------------------

To create a new content widget:

1. Navigate to **Marketing > Content Widgets** in the main menu.
2. Click **Create Content Widget** on the top right.

   .. note:: If you have more than one organization in your OroCommerce application, first select which organization to add a new content widget to.

3. Depending on the widget type, form fields are different:

   * **Contact Us Form** - Enables you to add a standard Contact Us form.

    .. image:: /user/img/marketing/content_widgets/contact_us.png
       :alt: Contact us content widget form

   * **Image Slider** - Enables you to configure and add an image slider.

    .. image:: /user/img/marketing/content_widgets/image_slider_1.png
       :alt: Image slider content widget form

    .. note:: You can add as many slides as necessary by clicking **Add** at the bottom of the *Slides* section.

            .. image:: /user/img/marketing/content_widgets/image_slider_2.png
               :alt: Image slider content widget form

   * **Copyright** - Enables you to add a full or shortened version of a copyright notice.

    .. image:: /user/img/marketing/content_widgets/copyright.png
       :alt: Copyright content widget form

4. Once you have provided all widget-specific details, click **Save and Close**.

   .. image:: /user/img/marketing/content_widgets/widget-view.png
      :alt: Content widget view page

   .. hint:: Each content widget may have various representations in the form of layouts. Layouts are defined by developers using the existing :ref:`layout update functionality <dev-doc-frontend-layouts-layout>`, which enables you to alternate between the pre-configured designs for each widget in the back-office.

             .. image:: /user/img/marketing/content_widgets/layout-dropdown.png
                :scale: 50%
                :align: center
                :alt: Select Layouts in the back-office

             Please be aware that layouts are theme-specific. For more information, please refer to the :ref:`CMS bundle documentation <how-to_create-content-widget-type>`.

Add a Content Widget to WYSIWYG Fields
--------------------------------------

You can add content widgets to WYSIWYG fields in your OroCommerce application, like content blocks, landing pages, etc.

To add a content widget to a field, drag the content widget element from the editor's manager panel, and drop it to the required location of the content field.

.. image:: /user/img/marketing/content_widgets/drag_cw.png
   :alt: Adding a content widget to a WYSIWYG field

All landing pages and content blocks where content widgets were used, are displayed in the **Usages** section of each content widget.

.. image:: /user/img/marketing/content_widgets/usages.png
   :alt: Landing page linked to a content widget displayed in the Usages section

