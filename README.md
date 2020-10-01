# Ansible Role: Nginx

Deploys and configures [nginx](https://www.nginx.com/).

## Requirements

None.

## Role Variables

| Variable       | Choices/**Default** | Comments                                                      |
| -------------- | ------------------- | ------------------------------------------------------------- |
| vhost_location | **""**, …           | The path to the directory containing virtual hosts to install |
| vhosts         | **[]**, …           | The list of vhosts to install                                 |

## Dependencies

None.

## Example Playbook

    - hosts: all
      become: true
      roles:
         - ansible-role-nginx

## License

Ansible-role-nginx is licensed under the [MIT license](https://github.com/zaszi/ansible-role-nginx/blob/master/LICENSE.md).
