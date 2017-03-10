# README-mestery.md

Simple notes for using this on scaleway:

To run the container:
* docker run -d --link postgres-for-ttrss:db --name=mestery-ttrss  -p 127.0.0.1:3000:443 root/docker-ttrss
