# architecture-docker-compose

## Getting Started
With default settings in docker-compose.yml, the following configuration is preset in host to streamline setup procedure.

Ensure /etc/hosts has these entries:
- proxy01.lockorder.cc
- ui01.lockorder.cc
- db01.lockorder.cc

Ensure these ports are not occupied in host:
- 80
- 8080
- 6080
- 7000

Create a directory structure to conform to this:
- reverse-proxy
- db-cassandra
- logs
