# selfoss-docker
Dockerfile for Selfoss RSS aggregator

Note: this image uses the default Selfoss config.

To run the latest stable tag (2.18) use:
```
docker-compose up
```
Then find the web interface at http://localhost:8390


To run the latest master version use:
```
docker-compose -f docker-compose.master.yml up
```
Then find the web interface at http://localhost:8391


To rebuild the master version with the latest code from git use:
```
docker-compose -f docker-compose.master.yml build --no-cache
```
