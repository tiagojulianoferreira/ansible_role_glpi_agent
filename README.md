glpi-agent
=========

Instala o GLPI Agent em sistemas Linux e Windows (ainda não implementado).

Requirements
------------

- Conexões SSH(Linux) e WinRM(Windows)

Role Variables
--------------

Em **default/main.yml** é necessário cadastrar as variáveis **perl_url_glpi_agent** e **glpi_agent_version**

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - glpi-agent

TO DO

- [x] Instala agentes em hosts Linux usando Perl
- [ ] Instala agentes em hosts Windows
  
License
-------

BSD

Author Information
------------------

Tiago J. Ferreira.
