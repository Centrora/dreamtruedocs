.. _manually-install-component:

Manually Installing the Component
*****************************************

If the server has the relatively strict PHP settings, such as a low value of **upload_max_filesize** or **memory_limit**, the installation by ``Upload Package File`` or ``Install from URL`` in Joomla! might fail. In this case, we can apply a manual method to install the component.

1. Download the install package ``com_moscribe.zip`` to the PC.

2. Extract the package to have all source files.

.. image:: https://cdn.dream-true.com/images/Tutorials/003_Extract_Package.jpg

3. Login the website FTP or go to the File Manager of the the Host Control Panel.

4. Create a new directory as ``membership`` in the ``/site_root/tmp`` folder.

.. image:: https://cdn.dream-true.com/images/Tutorials/004_Create_Folder.jpg

5. Upload all files which we have extracted in the step 2 to the new directory.

.. image:: https://cdn.dream-true.com/images/Tutorials/005_Upload_files.jpg

6. Go to the Joomla! menu ``Extensions`` --> ``Manage`` --> ``Install`` --> ``Install from Folder``, enter the absolute path of the about ``membership`` folder, for example,
::

  /home/sites/public_html/xxxxxx/tmp/membership

7. Click the ``Check & Install`` button.

Then the component will be installed. Please enter the component and :ref:`install-db`.

