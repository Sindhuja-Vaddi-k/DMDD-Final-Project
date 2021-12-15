
Execute the script All_Tab_Scripts.sql in sql developer.
Once the inserts are completed for All_Tab_Scripts table, run PROC_CREATE_TABLE.sql. This will create all the 11 database tables.
Once the tables are created, run the insert statements in Insertions.sql. This script will initialize the database.

Create all the procedures, views, sequences, packages, triggers, functions that are present in their respective folders.

To execute the procedures-
EXECUTE PROC_INSERT_UPDATE_CUST('CUST-890' , 'JAYA' , 'BALWANI' , 'RAJKUMAR' , 'FEMALE' , 'SINGLE' , 'balwanij@gmail.com' , 'PasswordJaya' , '10-dec-90');
EXECUTE PROC_ADD_CUST_CON ( 123 , 'CUST-890'  ,'34 CHEROKEE STREET' , 'APT 2' , 'BOSTON' , 'MA' , 'EAST' , 21762, 1234512345 );
EXECUTE PROC_ADD_CUST_PAYMENT (  'CUST-890' , 'DEBIT CARD' , 'VISA' , '12/22');
EXECUTE PROC_INSERT_VENDOR( 401, 'SEPHORA', 'MAKEUP' , SYSDATE, SYSDATE+365 );
EXECUTE PROC_ADD_VENDOR_ADDRESS( 999, 401 , 'sephora@gmail.com' , '30 South' , 'Huntington' , 'Boston' , 'MA' , 90321, 1234512345  );
EXECUTE PROC_ADD_PRODUCT_DETAILS ( 'PROD-123' , 'XYZ' , 401, 1 , 2, 'BLACK' , 3,  SYSDATE, 3 , 30  );


Execute Roles.txt file to create different roles in database.

