Zabbix 2.4 用 ansible

# how to use

- playbook.ymlのvarsにmysqlのroot,zabbixユーザのパスワードを記述してください
- hostsにzabbix-serverを構築するServerのIPアドレスを記述してください


# 実行

```
ansible-playbook -i hosts playbook.yml --ask-pass --ask-sudo-pass -vvvv
```
