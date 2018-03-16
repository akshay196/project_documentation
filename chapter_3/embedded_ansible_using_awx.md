## Embedded Ansible using AWX

- Background
  - Embedded Ansible in Fine Release
  - Ansible Tower
  - Setup Embedded Ansible (http://talk.manageiq.org/t/howto-setup-embedded-ansible/2291/2) (Do not write whole procedure)
- AWX intro
- How it is integrated in ManageIQ
  - 4 Docker containers
  - Watch for awx logs
  - Access awx bash and look for errors
- No problem of Ansibe Tower license

### Background

In ManageIQ Fine release, it is configured to use [Ansible Tower](https://www.ansible.com/products/tower) for automation. Integrating Ansible Tower in ManageIQ requires a tower license.

| Info | Procedure to setup Embedded Ansible in ManageIQ Fine is described in [Setup Embedded Ansible](http://talk.manageiq.org/t/howto-setup-embedded-ansible/2291) |
|------|:------|

In Gaprindashvili release of ManageIQ, Ansible Tower is replaced by AWX for implementation of Embedded Ansible. [AWX](https://github.com/ansible/awx) is open source project around the Ansible Tower codebase. Unlike Ansible Tower, AWX doesn't requires license to be added for enabling Embedded Ansible in ManageIQ.
