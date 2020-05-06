Solution: VPN - Active Directory Authenticated 
======================================================

This solution documents  all the necessary pieces required to setup a basic VPN for use with Active Directory Authentication.  

Objective:
----------

-  Gain an understanding of a basic VPN configuration

-  Gain an initial understanding of Active Directory AAA Objects

.. toctree::
   :maxdepth: 1
   :caption: Content:
   :glob:
  
   guide/guide.rst
   postman/postman.rst


Configuration Comments
------------------------

Access Blueprint Revision
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  - 35

Postman Collection(s)
^^^^^^^^^^^^^^^^^^^^
  - vpn.acme.com-ad-create.json
  - vpn.acme.com-ad-delete.json


APM Profile(s) 
^^^^^^^^^^^^
  - profile_Common_vpn.acme.com-psp.conf.tar


BIG-IP Versions Tested
^^^^^^^^^^^^^^^^^^^^^^
  - 15.1

BIG-IP Components used:
-----------------

* Virtual Server
 - HTTP Profile -https://support.f5.com/csp/article/K4707
 - Client-side SSL Profile -https://support.f5.com/csp/article/K14783
 - Connectivity profile
 - Access Profile
      + Active Directory AAA Object
      + Network Access Resource
      + IPv4 Lease Pool
      + Webtop
      + Webtop Sections




   

