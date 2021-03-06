.. _products--featured-products:

:oro_documentation_types: OroCommerce

Manage Featured Products
------------------------

.. begin_featured_products

You can mark some of the products as featured to display them in the Featured Products block on the main landing page (home page) in the storefront.

.. image:: /user/img/products/products/FeatruedProducts.png
   :alt: The way featured products are displayed in the storefront

Customize a Featured Products Segment
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can customize the way products are filtered for the featured products block by doing the following:

* Extend the number of products that are displayed in the Featured Products block,
* Provide additional filter on top of the default one (Product.IsFeatured is Yes).

Create a Custom Featured Product Segment for Organization or Website
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

To enable showing different products as featured on some websites, you may create
a new segments with custom filtering conditions and configure the organization
or website to use the customized version instead of the default one.

To create a new custom segment for featured products:

1. Navigate to **Reports & Segments > Manage Segments** in the main menu.

#. Click **Create Segment** on the top right of the page.

#. Configure a new segment to have a distinct name and the necessary filtering condition. For more detailed steps, please see :ref:`Create Segment <user-guide--business-intelligence--create-segments>` topic.

   **Sample Featured Products segment (default configuration)**

   .. image:: /user/img/products/products/FeaturedProductSegment.png
      :alt: Sample of the featured products segment

#. Click **Save**.

Now you can enable this segment to be the source of featured products in the :ref:`website <sys--websites--commerce--products--featured-products>` or :ref:`organization <sys--users--organization--commerce--products--featured-products>` configuration.


Mark a Product as Featured
^^^^^^^^^^^^^^^^^^^^^^^^^^

To mark a product as featured:

1. In the main menu, navigate to the **Products > Products**.
#. Hover over the |IcMore| **More Options** menu to the right of the item and click the |IcEdit| **Edit** icon to start editing its details.
#. In the **General** section, set **Is Featured** to *Yes*.
#. Click **Save**.


Remove a Product from Featured Products
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

To remove a product from Featured Products block, set **Is Featured** to *No* in the product details:

1. In the main menu, navigate to the **Products > Products**.
#. Hover over the |IcMore| **More Options** menu to the right of the item and click the |IcEdit| **Edit** icon to start editing its details.
#. In the **General** section, set **Is Featured** to *No*.
#. Click **Save**.

Configure the Featured Products Segment
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Configuring the Featured Product segment can be done globally, per website, and organization.

* :ref:`Create a featured products segment globally <sys--commerce--product--featured-products>`
* :ref:`Create a featured products segment per organization <sys--users--organization--commerce--products--featured-products>`
* :ref:`Create a featured products segment per website <sys--websites--commerce--products--featured-products>`

.. finish_featured_products

.. include:: /include/include-images.rst
   :start-after: begin
