# Remote access to  a PostgreSQL Database

| Description | Command |
|-------------|---------|
| Install Postgresql (if already installed skip this step | `` sudo apt update sudo`` ``sudo apt install postgresql postgresql-contrib`` |
| Enable service in time of pc boot | ``update-rc.d postgresql enable`` |
| Go to /etc/postgresql/<version>/main/ and Now Edit pg_hba.conf file | `` host all  all  (YOUR IP ADDRESS)/32   trust(any) `` |
| Now edit postgresql.conf file | edit this line `` listen_addresses = '*' `` | 
| Restart Postgresql service | `` sudo service postgresql restart `` |
  
:relaxed: Enjoy!!
