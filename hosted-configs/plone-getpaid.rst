.. Note:: `View config on GitHub`_
  :class: alert alert-info

Plone + PloneGetPaid
====================

E-commerce platform for Plone: getpaid. You want to try ``getpaid`` for Plone::

    $ virtualenv-2.7 .
    $ bin/pip install zc.buildout
    $ bin/buildout init

Edit the contents of **buildout.cfg** to contain *only*::

    [buildout]
    extends = https://raw.github.com/pythonpackages/buildout-plone-getpaid/master/4.3.x

Then run::

    $ bin/buildout

Followed by::

    $ bin/plone fg

At which point you should see::

    2012-01-09 19:53:26 INFO ZServer HTTP server started at Mon Jan  9 19:53:26
    2012
        Hostname: 0.0.0.0
        Port: 8080
    2012-01-09 19:53:29 WARNING ZODB.blob (13380) Blob dir
    /Users/aclark/Developer/test-plone/var/blobstorage/ has insecure mode setting
    2012-01-09 19:53:35 INFO PloneHotfix20110928 Hotfix installed.
    2012-01-09 19:53:35 INFO Zope Ready to handle requests

Open the following URL in your web browser:

 - http://127.0.0.1:8080

Click on "Create a new plone site" and should see:

.. image:: https://github.com/pythonpackages/pythonpackages-docs/raw/master/hosted-configs/getpaid1.png
   :class: thumbnail

.. include:: ../disqus.html

.. _`View config on GitHub`: https://github.com/pythonpackages/buildout-plone/blob/master/4.3.x

