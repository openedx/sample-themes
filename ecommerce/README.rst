Sample Themes for E-Commerce Service
====================================
This directory contains themes for E-Commerce Service,
following directory structure should be followed for each theme.


.. code-block:: text

   themes
      |
      └─ my-theme
          ├── README.rst
          ├── static
          |      └── images
          |      |     └── logo.png
          |      |
          |      └── sass
          |            └── partials
          |                   └── utilities
          |                           └── _variables.scss
          |
          └── templates
                └── oscar
                |     └── dashboard
                |             └── index.html
                └── 404.html

A more detailed description of how you apply themes to the E-Commerce service and guidelines for theming templates, assets and styles can be found here_.

.. _here: https://github.com/edx/ecommerce/blob/master/docs/theming.rst
