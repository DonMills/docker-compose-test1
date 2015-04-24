# docker-compose-test1
This is a quick first test of docker-compose.  It takes the ubuntu base, spins up 2 apache webservers
and 1 haproxy loadbalancer tied to port 8080 on the docker host.
To test:
http://localhost:8080
refreshing the page should change the server number...
