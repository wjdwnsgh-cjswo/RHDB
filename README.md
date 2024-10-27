# RHDB

This is a simple RHDB.

Discord : rha.rhs

Whole db in dict format : Get it by getDict()

RHDB Lite V1 Usage
1. Set DB
   rhdb_lite.set(db location) #resets when the program ends
2. Add category 
   rhdb_lite.addCategory(category name)
3. Reset category 
   rhdb_lite.resetCategory(category name)
4. Add category
   rhdb_lite.addCategory(category name) #Doesn't work if the category already exists
5. Save
   rhdb_lite.save(Whole db in dict format)
6. Get dict from rhdb
   rhdb_lite.getDict() # Need to set db first.
   : Return <Dict>
7. Change dict to rhdb 
   rhdb_lite.dictToDbFormat(Whole db in dict format)
   : Return <Str>

RHDB V1 is not developed yet.
Connecting with SQL, sending db with Image will be added (May be delayed)
get last edited time, get db created date, a simple encryption will be added. 
Command will be added. (Ex.Usage : "DELETE CATEGORY [category name]")

