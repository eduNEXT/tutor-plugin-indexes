Tutor Plugin Indexes
====================

Repository with the collection of Tutor Plugins used for edunext in their installations.

Usage
-----

To use this index in your instance you can follow the instructions in the `official Tutor Documentation`_.

Add the index with:

.. code-block:: bash
  
  tutor plugins index add https://raw.githubusercontent.com/eduNEXT/tutor-plugin-indexes/main/
  
Remove the index with:

.. code-block:: bash
  
  tutor plugins index remove https://raw.githubusercontent.com/eduNEXT/tutor-plugin-indexes/main/
  

If you need to update the cache, that means, fetching the latest changes in the index, use the command ``tutor plugins update``.


Update or Create an index
-------------------------

Please open a PR with the changes, you can follow the `official Tutor Documentation`_ to understand the folder structure
and the plugin syntax. 

License
-------

This software is licensed under the terms of the AGPLv3. See the LICENSE file for details.

.. _official Tutor Documentation: https://docs.tutor.edly.io/reference/indexes.html
