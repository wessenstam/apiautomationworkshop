.. _rest_nutanix_api_introduction:

----------------------------------
Nutanix REST API Explorer Overview
----------------------------------

Overview
++++++++



What is the Nutanix REST API explorer
+++++++++++++++++++++++++++++++++++++

The Nutanix REST API Explorer is written and formatted using an API framework called Swagger (governed by Apache license v2.0), used to describe and document RESTful APIs. The framework generates an interactive API document users can visualize and interact with, which Nutant’s commonly refer to as the Nutanix REST API Explorer.

The explorer is an expandable/collapsible, interactive hypertext document, organized by top-level resources (i.e. images, vms, hosts, storage containers, etc…), and their associated HTTP request operations (i.e**. GET, POST, DELETE, PUT**). When a resource operation is expanded, consumers are provided with descriptions, JSON Model definitions, and request/response panes for viewing messages and header and information.

Users navigate the explorer by scanning the document for a top-level resource (i.e. vms) they want to perform work on. Once a resource has been located, users can then expand the resource by performing a mouse-click on the resource name, exposing the supported HTTP request operations. Users can then interact with, and manipulate a resource instance using a given request operation from within the explorer view.

JSON Message-Body Declaration
.............................

The following illustration shows a message-body formatted in JSON used for creating a Virtual Machine (VM) using POST as defined using the Nutanix REST API Explorer.

.. figure:: images/image2.png

JSON Message Response Header
............................

The following illustration shows a message-body formatted in JSON for creating a Virtual Machine (VM) using POST from within the Nutanix REST API Explorer.

.. figure:: images/image3.png

Locate & Launch REST API Explorer
+++++++++++++++++++++++++++++++++

Now lets locate the Nutanix REST API Explorer.

Open \https://*<Prism-Central-IP>*:9440/ in a browser and log in.

From the navigation bar, click **Admin** at the top right corner, and then click **REST API Explorer**.
