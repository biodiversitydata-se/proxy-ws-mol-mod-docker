# proxy-ws-mol-mod

A dockerized NGINX reverse proxy setup for Swedish ASV database system (https://github.com/biodiversitydata-se/mol-mod/)

To enable SSL, put the SSL certifcate and key in the **certs** directory

To change domain names, change the values for **server_name**, **ssl_certificate** and **ssl_certificate_key** variables in the **conf.d/molecular.conf** file.

