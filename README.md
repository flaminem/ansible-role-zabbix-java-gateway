# Ansible Zabbix Java Gateway  Role

Installing and configuration of the Zabbix java gateway. Uses packages from http://www.zabbix.com.

## Usage
    ---
    - hosts: all
      remote_user: root
      gather_facts: yes
      roles:
      - zabbix-java-gateway
