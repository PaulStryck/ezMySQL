Completely based on Justin Vincents work. But now PSR-0 complient!

Functions..

	- $db->get_results - get multiple row result set from the database (or previously cached results)
	- $db->get_row -- get one row from the database (or previously cached results)
	- $db->get_col - get one column from query (or previously cached results) based on column offset
	- $db->get_var -- get one variable, from one row, from the database (or previously cached results)
	- $db->query -- send a query to the database (and if any results, cache them)
	- $db->debug - print last sql query and returned results (if any)
	- $db->vardump - print the contents and structure of any variable
	- $db->select -- select a new database to work with
	- $db->get_col_info - get information about one or all columns such as column name or type
	- $db = new db -- Initiate new db object.
