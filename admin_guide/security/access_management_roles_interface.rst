.. _access-management--roles-interface:

Role on the Interface
=======================

.. contents:: :local:
    :depth: 3

    

The information about a role is divided into four sections. 

|

.. image:: ../img/access_roles_management/roles_overview1.png 

|

General Section
^^^^^^^^^^^^^^^^

+-------+----------------------------------------------------------------+
| Field | Description                                                    |
+=======+================================================================+
| Role  | The name of the role. This value must be unique in the system. |
+-------+----------------------------------------------------------------+

Additional Section
^^^^^^^^^^^^^^^^^^^

+--------------+------------------------------------------------------------------------------------------------------+
| Field        | Description                                                                                          |
+==============+======================================================================================================+
| Description  | Short but meaningful description of the role.                                                        |
+--------------+------------------------------------------------------------------------------------------------------+
| Organization | Which organization this role is applicable within.                                                   |
|              | Value **System-Wide** means that this role is applicable to all organizations defined in the system. |
+--------------+------------------------------------------------------------------------------------------------------+


Entity Section
^^^^^^^^^^^^^^^

This section contains information about permissions included in a role. 

For convenience, permissions are grouped in tabs by functions they control:

- **All**—All the permissions available on the other four tabs.

- **Account Management**—Access to the account management. 

- **Marketing**—Access to the data useful for marketing team.

- **Sales data**—Access to the data useful for sales team. 

- **System Capabilities**—Access to the system functionalities.
  

Each tab, except **System Capabilities**, is divided into two sections: 

- With the list of 'action on entity' permissions.

- With the list of capabilities.

The **System Capabilities** tab lists only capabilities that control access to the system functionalities. 

|

.. image:: ../img/access_roles_management/roles_overview2.png 

|

It is divided itself in the following sections:

- **Address**—A permission that defines whether a user can see drop-down country, address lists when they fill in address forms. 

- **Application**—Access to system parts of OroCRM application (job queue, system configuration, etc.) or additional extension of 'action on entity' permissions(whether a user can share grid views, change passwords of other users, etc.).
 
- **Calendar**—Access to management of system calendars, etc. 

- **Entity**—Permissions that define whether a user can import or export entity records, find them via the search functionality, etc.



For more information about the system capabilities, see the `Capabilities List <./admin-capabilities>`.


Users Section
^^^^^^^^^^^^^^

The list of users that have this role. 

|

.. image:: ../img/access_roles_management/roles_userssection.png 

|


Links
------

For general overview of roles, see the :ref:`Roles Management <user-guide-user-management-permissions-roles>` guide.

For what actions you can perform with roles, see the `Actions with Roles <./access-management-roles-actions>`__ guide.

For examples on roles application, see the :ref:`Access Configuration Examples <access-management--examples>` guide.



.. |IcRemove| image:: /img/buttons/IcRemove.png
	:align: middle

.. |IcClone| image:: /img/buttons/IcClone.png
	:align: middle

.. |IcDelete| image:: /img/buttons/IcDelete.png
	:align: middle