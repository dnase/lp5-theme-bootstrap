lp5-theme-bootstrap
===================

Luminis 5 default theme with bootstrap CSS and Javascript added for responsive layout.

Create a .war file in order to deploy.

Example (from theme base directory):
jar -cvf LP5_Corp_Bootstrap.war *

the .war can then be deployed to $CP_ROOT/products/liferay/liferay-admin/deploy (admin server[s]) and $CP_ROOT/products/liferay/liferay-portal/deploy (web server[s])

In order to get this to work, you need a layout that will make use of the responsive theme. I would recommend creating your own bootstrap display template, or using Dustin Sier's (https://github.com/MiracleManS/Liferay-Luminis-Bootstrap-Layouts)
