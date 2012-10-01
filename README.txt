------------------------
NOTIFY MODULE README
------------------------

This is a simple notification module. It provides e-mail notifications to
members about updates and changes to the Drupal web site.

Send comments via the issues queue on drupal.org:
http://drupal.org/project/issues/notify

------------------------
REQUIREMENTS
------------------------

This module requires a supported version of Drupal and cron to be
running.

------------------------
INSTALLATION
------------------------

1. Extract the notify module directory, including all its subdirectories, into
   your sites/all/modules directory.

2. Enable the notify module on the Modules list page.
   The database tables will be created automagically for you at this point.

3. Modify permissions on the People >> Permissions page.

4. Find the module in the Modules list page and click the Configuration link
   to edit the settings to your liking.  You can also navigate directly to
   admin/config/notify.

   Note: e-mail updates can only happen as frequently as the cron is setup to.
   Check your cron settings.

5. To enable your notification preferences, click on the "My notification
   settings" on the "My account" page. Or, similarly go to another user's
   account page at user/<user_id_here> to modify his or her personal settings.

6. Additional options can be set at Administer >> User management >> Users by
   clicking the "Notification settings" tab.

------------------------
AUTHOR / MAINTAINER
------------------------

Kjartan Mannes <kjartan@drop.org> is the original author.

Rob Barreca <rob@electronicinsight.com> was a previous maintainer.

Matt Chapman <matt@ninjitsuweb.com> is the current maintainer.

Ishmael Sanchez (http://ishmaelsanchez.com),
Ward Poelmans <wpoely86@gmail.com> and
John Oltman <john.oltman@sitebasin.com> co-developed the Drupal 7 port.

------------------------
RELATED PROJECTS & ALTERNATIVES
------------------------

http://drupal.org/project/notify_by_views
http://drupal.org/project/subscriptions
http://drupal.org/project/notifications

------------------------
WISHLIST
-----------------------

-Templated emails
