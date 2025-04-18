# wg-ansible

wg-ansible can be used to easily deploy

## Requirements

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

## Role Variables

| Variable Name       | Default Value                                        |
| ------------------- | ---------------------------------------------------- |
| client_ip_address   | TODO: automate checking how many peers are connected |
| allowed_ips         | 10.0.0.0/24                                          |
| vpn_server_port     | 51820                                                |
| keepalive           | 25                                                   |
| server_public_key   | None                                                 |
| vpn_server_endpoint | None                                                 |

## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

## License

BSD

## Author Information

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
