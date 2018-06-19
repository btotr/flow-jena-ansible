Apache Jena Fuseki Role (WIP)
=============================

Installs Apache Jena

# USAGE
Add inventory (hosts) and run:
```ansible-playbook fuseki.yml -i ./hosts```

# TODO
localhostfilter shiro (only works on localhost now)
systemd startup (has some troubles. manual ``` sudo /usr/local/fuseki/fuseki-server --mem --port=8080  /default  ```)
install vocab from github