Automation mesh deployment examples
=========

This repo contains some example mesh configurations and associated topology.dot files.

Generating dot files
------------

* Download AAP installer
* Update inventory with required mesh configuration
* Run ./setup.sh 

```
./setup.sh -- --tags generate_dot_file
```

This playbook deploys to AWS so needs python boto, boto3 and botocore modules. Also needs AWS credentials.

Visualise mesh configuration
--------------

Topology will be created in mesh-topology.dot file in pwd. You can visualise the mesh configuration by pasting the contents into https://dreampuf.github.io/GraphvizOnline
