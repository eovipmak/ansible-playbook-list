# ansible-playbook-list
List of Ansible playbooks

## 1. Microsoft SQL Server in docker container (support 2017, 2019 and 2022 version)
```
ansible-playbook mssql.yaml -e mssql_version="<version>" -e mssql_sa_password="<YourStrong!Passw0rd>" -e mssql_exposed_port="<Port>"
```
Ex:
```
ansible-playbook mssql.yaml -e mssql_version="2019" -e mssql_sa_password="iRYUNA40658WSU" -e mssql_exposed_port="1433"
```
