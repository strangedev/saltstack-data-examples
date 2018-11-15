# saltstack-data-examples

Example data for use with [saltstack-states](https://github.com/EducationalTechnologies/saltstack-states).

The data contained in this repository is a template for what data is required by `saltstack_sates`.
When setting up salstack on your environment, you should provide your own data.

## Contents

### `config`

This directory contains config files which are deployed to the minions. The config files are named according
to the service they belong to.


### `ssh-keys`

This directory contains public keys for setting up ssh authentication. To set up ssh authentication for a user,
place their ssh keys into this directory, follwing the naming convention: `username.id_rsa.pub`.
