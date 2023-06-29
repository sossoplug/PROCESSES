
# Migrating a database from 4D to MySQL process:

## 1. Database Schema: Analyze the structure of the 4D database and map it to a corresponding structure in MySQL. Identify tables, columns, indexes, relationships, and any other database objects that need to be migrated.

###

#
#


## 2. Data Conversion: Export the data from the 4D database and convert it into a format that can be imported into MySQL. This may involve exporting the data to CSV files or using specific tools or scripts to handle the conversion.

###

#
#


## 3. Create MySQL Database: Set up a new MySQL database where you will import the data from the 4D database. Ensure that the MySQL server is installed and configured properly.
#

###

#
#


## 4. Import Data: Use the MySQL tools or utilities (such as the mysql command-line tool or a graphical tool like phpMyAdmin) to import the converted data into the MySQL database. This may involve creating the necessary tables and importing the data from the converted files.

###

#
#


## 5. Update Application Code: If you have an application that interacts with the 4D database, you'll need to update the code to work with the MySQL database. This includes modifying the database connection settings, SQL queries, and any other database-specific operations.
#

###

#
#



## 6. Test and Verify: After the migration is complete, thoroughly test the application to ensure that the data is intact and the functionality works as expected. Verify that the data has been migrated correctly and that the application performs as intended with the new MySQL database.

###

# QUESTIONS
#
### Point Initial: Est ce qu'on ai Favorable a recommencer le processur d'importation depuis le debut ? 
#
### Ordre d'importation: Faut il importer les tables Parents avant les tables enfants ?
#

#
### Processur Nettoyage: Comment tu nettoie ton csv (Regex ou autre)?
#

