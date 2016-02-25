User Permissions
================

Users are given permissions through User Groups
-----------------------------------------------

Permissions to a calendar are given by User Groups. Each User Group contains a set of users, and some permissions those users are given.

To create a new User Group or see an existing one, go to "calendar admin" and "user groups".

Adding a user to a group
------------------------

Users can be added to groups in one of two ways.

Firstly they can be directly included in a group by their username.

Secondly a group can be set to automatically include:

  *  All Anonymous users
  *  All signed in users
  *  All signed in users who have verified their account

Adding or removing permissions to a group
-----------------------------------------

You can add and remove permissions to a group from the "Manage Permissions" tab.

Some permissions automatically include other permissions. For instance, "CALENDAR_CHANGE" is a general permission that includes "EVENTS_CHANGE", "GROUPS_CHANGE" and more.

Permissions that can be assigned
--------------------------------

Note the permissions you have available to you will depend on what extensions you have installed.

org.openacalendar - CALENDAR_ADMINISTRATE
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This gives permission to the users

org.openacalendar - CALENDAR_CHANGE
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This is a catch all permission that automatically includes all the permissions below.

org.openacalendar - AREAS_CHANGE
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This gives permission to the users to edit Areas on the calendar. Any such users can edit any Area on the calendar, regardless of whether they created it or not.

Note if the "Physical Events" feature is turned off no user will be able to do this, what ever permissions they have.

org.openacalendar - EVENTS_CHANGE
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This gives permission to the users to edit Events on the calendar. Any such users can edit any Event on the calendar, regardless of whether they created it or not.

Note this includes permissions to set Groups, Venues, Areas, Tags, etc for a particular Event.
So if a user has this permission but not the VENUES_CHANGE permission, it simply means they can not create new venues. They can still say an event is at an existing venue another user has created.

org.openacalendar - GROUPS_CHANGE
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This gives permission to the users to edit Groups on the calendar. Any such users can edit any Group on the calendar, regardless of whether they created it or not.

Note if the "Group" feature is turned off no user will be able to do this, what ever permissions they have.


org.openacalendar - IMPORTURL_CHANGE
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This gives permission to the users to edit Imports on the calendar. Any such users can edit any Import on the calendar, regardless of whether they created it or not.

Note if the "Importer" feature is turned off no user will be able to do this, what ever permissions they have.

org.openacalendar - TAGS_CHANGE
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This gives permission to the users to edit Tags on the calendar. Any such users can edit any Tag on the calendar, regardless of whether they created it or not.

Note if the "Tag" feature is turned off no user will be able to do this, what ever permissions they have.


org.openacalendar - VENUES_CHANGE
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This gives permission to the users to edit Venues on the calendar. Any such users can edit any Venue on the calendar, regardless of whether they created it or not.

Note if the "Physical Events" feature is turned off no user will be able to do this, what ever permissions they have.


org.openacalendar - MEDIAS_CHANGE
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This gives permission to the users to edit Media on the calendar. Any such users can edit any Media on the calendar, regardless of whether they uploaded it or not.


Excluding users in Multi Site mode
----------------------------------

TODO

What permissions does a particular user have?
---------------------------------------------

As permissions are given through groups, it can be difficult to see what permissions a particular user has sometimes.

Go to "calendar admin" and "users" to see what permissions a user who falls into one of these groups will have:

*  All Anonymous users
*  All signed in users
*  All signed in users who have verified their account
