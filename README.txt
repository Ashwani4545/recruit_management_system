Since this is an information system, the code cannot be used as is;  you will need 
to configure settings to match your server, set up an authentication system script, 
and populate various fields in the database before you will see any results.

You can set a bypass account name in misc/release_constants.inc so you can log in 
initially without setting up an authentication system.  Set ADMIN_ENABLED and/or 
STUDENT_ENABLED to TRUE, and set login names (ADMIN_LOGIN and STUDENT_LOGIN) in the 
secured_constants file. Using these logins, you can access the admin (OFFICE) 
userlevel and student userlevel without a password. In a production environment, 
always set ADMIN_ENABLED and STUDENT_ENABLED to FALSE.

Partway through our project, we switched to using the PEAR coding conventions for 
our PHP code.  As PEAR was in beta at the time, and has changed quite a bit since, 
our coding style has changed a few times to match its variations.  PEAR is now no longer 
in beta, so in future this should become less of a problem.  New code should be 
consistent with the latest PEAR standards, found at: 
http://pear.php.net/manual/en/standards.php

The ADOdb library as a database abstraction layer which supports a 
number of popular databases.  When coding, please use only wrapper calls; 
never use mysql (postgres, etc.) calls directly. See the SQL documentation on our 
website for more information.

 Our Sourceforge page, accessible from our 
website, has forums that may also provide you with information and help.

Thanks for using Mamook(R) Software
