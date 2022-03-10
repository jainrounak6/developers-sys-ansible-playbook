# Ansible Script for development environment

This ansible playbook will install required packages for development environment on Debian (Ubuntu) platform.

--------------------------------------------------------


####command:

```
ansible-playbook -i hosts main.yml --extra-vars "ansible_sudo_pass=password" --extra-vars "php_version=8" --extra-vars "node_version=16" --flush-cache
```

--------------------------------------------------------

# _License & Support_
##### _Developers : [Rounak Jain](mailto:jainrounak1997@outlook.com)_
<div align=center>
    <a href="https://www.linkedin.com/in/rounak-jain-devops/"><img src="https://img.shields.io/badge/Linkedin-0077b5?style=flat&logo=linkedin" alt="LinkedIn" /></a>
    <a href="https://www.upwork.com/freelancers/~01ef046d4e14ed4536"><img src="https://img.shields.io/badge/Upwork-494949?style=flat&logo=upwork" alt="UpWork" /></a>
    <a href="https://stackoverflow.com/users/15105759/rounak-jain"><img src="https://img.shields.io/badge/Stack Overflow-f48024?style=flat&logo=stackoverflow&logoColor=white" alt="Stack Overflow" /></a>
    <a href="https://t.me/iamrjrocks"><img src="https://img.shields.io/badge/Telegram-0088cc?style=flat&logo=telegram" alt="Telegram" /></a>
</div>