qchainage
=========

Chainage Plugin for QGIS
QChainage is a tool to do linear referencing on lines and polylines.

QChainage can:

- chainage only selected features or all features
- chainage from start to endpoint or the whole feature (or any other combinations)
- define offset and interval parameters
- define a number of parts in which the line should be separated
- force adding an endpoint to the line

Resulting layer is currently a "memory layer" which can be exported by the "save as" function to any vector format.

=================
This plugin was changed for a specifc demand.
1. Now it not create the first and de last point on the line
2. The number of points (number os parts + 1) is define by the <id> field
