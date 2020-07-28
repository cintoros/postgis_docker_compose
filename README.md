see also https://github.com/kartoza/docker-postgis

firsttime setup:
> psql -h localhost -U docker  -p 5432 postgres  
> docker  
> CREATE ROLE role WITH LOGIN PASSWORD 'password' SUPERUSER;  

NOTE: to connect you need to select the postgres database this can be done over any database tool 

startup (Ctrl+C for shutdown)
> ./start.sh 

