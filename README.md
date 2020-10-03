# Ansible - Roles for server setup and Elixir app deployment

A collection of ansible-roles / tasks / playbooks to bootstrap servers (mostly Ubuntu). Includes roles to set up a user to run elixir apps, deploy new versions with a same-server blue/green deployment and setting up Postgres.

**USE AT YOUR OWN RISK.**


### Usage
Best approach is to git subtree this project to where you need it (from the project root). You can then make changes to roles/playbooks/whatever as required. This repo can be seen as starting point.

```bash
  git subtree add --prefix ./provisioning https://github.com/tuacker/ansible-roles.git main --squash
```

If new changes need to be pulled in after a while, run this:

```bash
  git subtree pull --prefix ./provisioning https://github.com/tuacker/ansible-roles.git main --squash
```
