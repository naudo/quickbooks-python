### v0.1.3

* Changed the namespace for `quickbooks.quickbooks` to `quickbooks.client`
* Made RealmId (company_id) required as QBO will bomb out if not passed for certain queries
* Remove documentation that implies needing to install rauth seperately

### v0.1.1

* Configured package for distribution

### v0.1.0

* Well, versioning :)
* Removed a lot of extraneous method calls that have essentially been replaced with query_object().