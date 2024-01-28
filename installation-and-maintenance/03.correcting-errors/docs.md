# Correcting Errors

There are certain errors in the system which can be easily corrected by an administrator. Indication of such problems could be "Bad Server Response" errors while you visit the list or detail page for some entity or record.
This errors can be corrected by rebuilding database and/or clearing the system cache.

## Database Rebuild

AtroCore uses its own ORM system. It means that the database structure is first described as metadata with the help of JSON files. This metadata is synchronized than with the real database structure.
Sometimes, some system errors result in differences between the database structure and these metadata. To solve this kind of problems the feature `Rebuild Database` was implemented.

In this case go to "Administration > Settings" and click on the link `Rebuild Database` to actualize your database structure. If it does not help, contact the support.

## Clearing System Cache

Metadata and frontend are usually cached. In very seldom case it may results in errors. To solve these errors go to "Administration > System > Settings" and deactivate the checkbox for `Use Cache`.
Than click on the Function `Clear Cache` in the system section in the Administration. To be sure you have no problems with the database structure click on `Rebuild Database` in the same section.
After everything is done you can activate the use of cache again, go to go to "Administration > System > Settings" for that.



