# Ansible Role gitlab-runner
This role installs and configures a gitlab-runner with docker.

# TODO
- pull in docker in molecule and install it (can we do this without force stating a version but just use latest?)
- tests: `gitlab-ci-multi-runner status` exit status

# Example play
An example play can be found in `molecule/install/playbook.yml`

# Requirements
- You will need a gitlab server with it :)
- Go to the gitlab webui, generate a runner token and use it in the play vars
- blunix.role-docker

# License
Apache-2.0

# License
Apache-2.0

# Author Information
Service and support for orchestrated hosting environments,
continuous integration/deployment/delivery and various Linux
and open-source technology stacks are available from:

```
Blunix GmbH - Consulting for Linux Hosting 24/7
Glogauer Straße 21
10999 Berlin - Germany

Web: www.blunix.org
Email: service[at]blunix.org
Phone: (+49) 30 / 12 08 39 90
```
