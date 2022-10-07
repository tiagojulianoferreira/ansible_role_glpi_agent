glpi-agent
=========

Instala o GLPI Agent em sistemas Linux e ~~Windows~~ (ainda não implementado).

Requirements
------------

- Conexões SSH(Linux) e ~~WinRM(Windows)~~

Role Variables
--------------

Em **default/main.yml** é necessário cadastrar as variáveis **perl_url_glpi_agent**, **glpi_agent_version** e **server** (API Server do GLPI)

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ansible_role_glpi_agent

TO DO

- [x] Instala agentes em hosts Linux usando Perl
- [ ] Instala agentes em hosts Windows
- [ ] Estudar alternativas para o módulo shell (idempotência)
  
License
-------

BSD

Author Information
------------------

Tiago J. Ferreira.
