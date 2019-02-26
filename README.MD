# Keycloak MySQL Playbook

A playbook for running Keycloak and MySQL on Docker.
Database data is persisted in a docker volume.

## Running

To deploy in dev run commande
`$ sh run_dev.sh`

To deploy in prod run commande
`$ sh run_prod.sh`

## Personalization

### Versions and Volume

To configure keycloak and MySQL versions or the data volume you can edit the file `group_vars/all`.

### Environment Hosts

You can configure hosts in the files:

- dev : `inventories/dev/hosts`
- prod : `inventories/prod/hosts`

### Variables

Variables are in those files:

- dev : `inventories/dev/group_vars/all`
- prod : `inventories/prod/group_vars/all`
