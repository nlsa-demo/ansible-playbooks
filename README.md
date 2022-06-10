# Ansible Playbook Automation

This repository contains an ansible playbook to automatically the Natural Language Search Accelerator Demo.

## Deployment via IBM Cloud Schematics
Integration as Action in Schematics

#### Create Action
![action creation](/imgs/action-create.png)

#### Configure Action
![action config](/imgs/action-config.png)

Public Github Link containing ansbile playbook:
```https://github.com/nlsa-demo/ansible-playbooks```

Varibles to set:
- registry_api_key 
- apikey 
- resource_group

## Running locally

If you haven't install ansible, follow the [instructions](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html]).

- If running locally, set the variables `registry_api_key`and `apikey` in the `playbook.yml`.
- Adjust the `resource_group` to match your targeted resource ground name.
- Adjust the `host` to `localhost`.

Run 
```bash
$ ansible-playbook playbook.yml
```