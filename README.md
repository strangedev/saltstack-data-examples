# saltstack-data-examples

Example data for use with [saltstack-states](https://github.com/strangedev/saltstack-states).

The data contained in this repository is a template for what data is required by `saltstack_sates`.
When setting up salstack on your environment, you should provide your own data.

The purpose of separating this into it's own repository and not including data with the states is, that data
may contain secrets, which should not be added to a public vcs, or not added to a vcs at all. Users of the
saltstack-states repo may choose how they want to provide their data.

## Contents

### `config`

This directory contains config files which are deployed to the minions. The config files are named according
to the service they belong to.


### `ssh-keys`

This directory contains public keys for setting up ssh authentication. To set up ssh authentication for a user,
place their ssh keys into this directory, follwing the naming convention: `username.id_rsa.pub`.
