Auth User Badge
==============

This is a workaround for using [Autchcache](https://www.drupal.org/project/authcache) with [Open Atrium 2](https://www.drupal.org/project/openatrium)'s OA User Badge, which displays the username and a personalized menu. This module essentially pulls the badge out of the oa_toolbar module so it can be displayed as a block in your theme's region, which is necessary because [Authcache doesn't support Panelizer](https://www.drupal.org/node/2703789). If you'd like to use Authcache with OA2 and would like to dynamically load the OA User Badge as a personalized fragment, you can enable this module and display the Auth User Badge block in one of your theme's regions at /admin/structure/block. You can then configure Authcache for the block so it will lazy load. You can then disable the OA User Badge in the OA Toolbar mini panel.

----------

See Also
-------------

 - "[Authcache not working on content in Mini Panels](https://www.drupal.org/node/2231701)"
 - "[Add Authcache support for Organic Groups](https://www.drupal.org/node/2474473)"
 - "[Add Authcache support for Organic Groups / Open Atrium](https://www.drupal.org/node/2474327)"

License
-------------

GNU GENERAL PUBLIC LICENSE
