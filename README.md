iiif_image_field
================

Drupal module for adding IIIF Images to content types.

1. Enable the module via drush `drush en iiif_image_field`.
2. You can configure your server and API version via the Modules manager or Admin > Config > Media > IIIF Image Field
2. Go to Structure > Content Types > yourContentType > Manage Fields
3. Add a IIIF Image field and the IIIF Image Formatter should be automatically selected.
4. Click on Manage Display and make sure your field is visible. Adjust settings for your view mode.
5. Edit content and add your IIIF Image ID and a label/caption/citation

Note: If you need to uninstall, you must make sure that the IIIF Image Field is deleted from all Content Types that use it.

License
====
Some libraries licenses are amiguous.  Currently sorting that out...

The IIIF Image Field Module itself is licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
