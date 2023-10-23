# y-jet

Jet Roles, Scripts and Modules 

## Jet References

| Resource | URL                                                   |
|----------|-------------------------------------------------------|
| Homepage | https://www.jetporch.com/                             |
| Discord  | https://www.jetporch.com/community/discord-chat       |
| Roadmap  | https://trello.com/b/57AyE7ka/jetporch-public-roadmap |
| Status   | https://www.jetporch.com/community/status             |
| Source   | https://sr.ht/~mpdehaan/jetporch/                     |

## Comparibles Tools and Services

| Comparable     | Description                     |
|----------------|---------------------------------|
| Ansible        | Jet-like with Python Dependency |
| Proxmox        | Hypervisor                      |
| CloudInit      | Image Config                    |
| Packer         | Image Prep                      |
| Docker         | Containers                      |
| Docker Compose | Container Coordination          |
| Docker Swarm   | Container Deploy SW             |
| Kamal          | Container Deploy SW             |
| Fly            | Container Deploy SAAS           |

## External Modules 

https://www.jetporch.com/developer-guides/external-module-spec 

- modules are bash scripts
- modules read JSON from stdin and write JSON to stdout 
- modules depend on `jq`. 
- module names prefaced with `jm_<>`
- write curry function?  probably modules will not be composable in Jet...

## Scripts 

- https://www.jetporch.com/modules/commands#script 
- https://www.jetporch.com/modules/commands#controlling-when-failures-are-returned 
- https://www.jetporch.com/modules/commands#controlling-when-changes-are-reported 
- https://www.jetporch.com/playbooks/tasks-and-task-modifiers#with-statements 
- https://www.jetporch.com/playbooks/tasks-and-task-modifiers#condition 

- script names prefaced with `js_<>`

