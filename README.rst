#######################
 jquery.cmis.js README
#######################

jquery.cmis.js is a library to simplify the parsing of CMIS response. The implementation of the transportation layer has not been included because you might want to use different method of authentication or to send request to the CMIS server. For example, you might want to connect to a CMIS server that is on another domain name, and, because of the cross domain policy of browsers, you have to use a proxy on your domain.

It has been developed for the xCMIS_ implementation, but it is has been tested successfully with Alfresco and Nuxeo (Apache Chemistry_). Let us know if you test with other implementation, we will add them to the list.

Using it
========

everything starts by CMIS.parse(xml)
see the jsdoc: http://jeremi.github.com/jquery-cmis/symbols/CMIS.html

Links:
======

* jsdoc: http://jeremi.github.com/jquery-cmis/symbols/CMIS.html
* eXo Platform: http://www.exoplatform.org
* xCMIS: http://code.google.com/p/xcmis/
* CMIS: http://www.oasis-open.org/committees/cmis/

.. _xCMIS: http://code.google.com/p/xcmis/
.. _Chemistry: http://incubator.apache.org/chemistry/
.. _CMIS: http://www.oasis-open.org/committees/cmis/