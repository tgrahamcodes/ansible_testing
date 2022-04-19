  #### **Ansible**:
    - Simple IT engine that automates many IT needs
    - YAML (in the form of Ansible Playbooks)
    - Ansible modules are programs designed to model the state of the system. Used over SSH.
    - Modules can be on any machine
    - Agentless
    - Azure, Windows, AWS, Linux

    Examples:
    - Make one change on control station, i.e /etc/blah will change on all servers
    - Routers you can do this for too
    - Push/pull
      - Push module configs
      - Pull configs
    - ansible linux -m ping
    - ansible linux -a "cat /etc/os/release"
  
    Playbooks:
      - YAML files stands for data serialization
        - Stands for Yaml
          - Yaml Ain't Markup Language (.yml)
  
