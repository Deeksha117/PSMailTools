# 0.1.2 ( April 11, 2018 )

FEATURES:

* Test-SPFRecord : Added `-FindIp <ipaddr>` which will recursively follow the SPF record for a domain and determine if the specified IP is covered anywhere in the record. (Currently only supports IPv4 addresses.)

IMPROVEMENTS:

* ConvertTo-SPFTree : Changed an internal System.Array object to a 'System.Collections.Generic.List[System.Object]' object to improve performance for large records.

BUG FIXES:

* ConvertTo-SPFTree : Fixed an issue with the display of mx mechanisms when a domain has more than one mx record.

# 0.1.1 ( April 10, 2018 )

IMPROVEMENTS:

* Modified the build script to concatinate a number of the internal script files which improves performance in some edge cases.

BUG FIXES:

* Fixed a bug where the release zip did not contain cmdlet help generated by PlatyPS.
* Fixed a bug where the release zip did not contain a file catalog.

# 0.1.0 ( April 08, 2018 )

This was the initial public release.