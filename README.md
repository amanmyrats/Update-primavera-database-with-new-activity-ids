# Update-primavera-database-with-new-activity-ids
This code will take newly created activity IDs, and send them to primavera database and update it.

First we fetch all existing activities with their then assigned activity IDs. Then we generate new activity IDs with special activity
  ID generator(which is my anothor repository).
Then we send it back to primavera database.

Sample excel file contains 6 modules:
  functions
  module_general
  module_getActivities
  Module_index
  Module_test
  module_variables


*I could not upload my sample excel file here, if anyone know how to do it, please let me know.
