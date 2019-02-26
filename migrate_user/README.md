Installation guidelines:
======================== 
 - Copy user.csv file into sites/default/files/ directory
 - Create two more plain text fields "field_first_name" & "field_last_name" 
   for the user entity from the url http://migration.lndo.site/admin/config/people/accounts/fields
 - Create one more user roles "migrationuser"
 - Install and enable the module and it's dependencies.
 
Migration Process:
==================
 - using migrate_tools run the migration as per below:
   1. drush migrate:status (to check all the list of migration with it's status)
   2. drush migrate:import migration_unique_id (Process the migration)
   
Your are done with migration basics.
   
