# Mongo DB Replica Set Local Development
This will setup a local replica set for you to work with using the lastest version of MongoDB.

## Installation
1. Modify hostnames as per your liking. We use mongo1 and mongo2 for our demo.
2. Add your hostnames into `/etc/hosts` as:
  ```
  127.0.0.1 mongo1 mongo2
  ```
3. Update `scripts/setup.sh` to include your modified hostnames.
