# SQLI-Lab

SQLI-LABS is a platform to learn SQLI Following labs are covered for GET and POST scenarios:

    Error Based Injections (Union Select)
        String
        Intiger

    Error Based Injections (Double Injection Based)

    BLIND Injections: 1.Boolian Based 2.Time Based

    Update Query Injection.

    Insert Query Injections.

    Header Injections. 1.Referer based. 2.UserAgent based. 3.Cookie based.

    Second Order Injections

    Bypassing WAF
        Bypassing Blacklist filters Stripping comments Stripping OR & AND Stripping SPACES and COMMENTS Stripping UNION & SELECT
        Impidence mismatch

    Bypass addslashes()

    Bypassing mysql_real_escape_string. (under special conditions)

    Stacked SQL injections.

    Secondary channel extraction

======================================================================================== Install Instructions:

    Unzip the contents inside the apache folder, for example under /var/www
    This will create a folder sql-labs under it. else you can use git command from within /var/www folder. /var/www folder and then use following command> git clone https://github.com/Audi-1/sqli-labs.git sqli-labs
    Open the file "db-creds.inc" which is under sql-connections folder inside the sql-labs folder.
    Update your MYSQL database username and password.(default for Backtrack are used root:toor)
    From your browser access the sql-labs folder to load index.html
    Click on the link setup/resetDB to create database, create tables and populate Data.
    Labs ready to be used, click on lesson number to open the lesson page.
    Enjoy the labs

==========================================================================================

Corrosponding walkthrough video tutorials and explainations can be found at:

    http://dummy2dummies.blogspot.com
    http://www.securitytube.net/user/Audi
    https://www.facebook.com/sqlilabs

you can also find the read along book at https://leanpub.com/SQLI-LABS, work is under process.

==========================================================================================

Challenge Section added: Less-54 to Less - 61 special challenge lessons added to repository for testing skills learnt from the other Lab lessons.

==========================================================================================
