> **Important:** Currently all requests to API v2.0 must append $schemaversion=2.0 to the request URL to work properly. This is to uptake the new improved $metadata model avaliable from Business Central 17. An update will be applied shortly to apply the schemaversion automatically to API v2.0. For all other APIs $schemaversion=1.0 will be the default, unless specified in the request URL with $schemaversion=2.0. A solution is being worked on, where the schemaversion will be defined in the extension.