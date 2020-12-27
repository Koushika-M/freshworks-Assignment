# freshworks-Assignment
*Build a file-based key-value data store that supports the basic CRD (create, read, and delete) operations. This data store is meant to be used as a local storage for one single process on one laptop. The data store must be exposed as a library to clients that can instantiate a class and work with the data store.*



After class, the key value datastore is created as 'database.json' in a user-defined address. If no address was provided, it defaults to the current working address. 
This program supports thread safety, single client process at a time and Limited file size(1 gb)
