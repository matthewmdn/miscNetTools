This script is used to get elastalert up and running quickly on a host.

Done:
- Installs dependencies (Centos 7)
- Installs elastalert (Centos 7)
- Creates a working directory tree in /opt
- Copies an example config

Todo:
- Distribution detection
- Elasticsearch version detection for pre-reqs (see current comments in main script)
- Maybe a config section with switches for cluster and credentials
- Get elastalert running as a service