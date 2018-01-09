# Docker

Questions

*   What are the advantages of a separate postgres container

        *   Easier setup for now - and they recommend 1 service per container in their best practices guid

*   What is the best way to pass credentials? As "-e PASS=1234" when running a docker instance?

        *   Yes - this is a lot easier when using Ansible to manage the images
    *   1 concern - will credentials show up in the process list??

*   Where should we build images - locally and push to repository or on the docker host?
*   How do we manage image labels?