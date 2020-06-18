# daixijun.mysqlshell

[![Build Status](https://github.com/daixijun/ansible-role-mysql-shell/workflows/build/badge.svg)](https://github.com/daixijun/ansible-role-mysql-shell/actions)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-daixijun.mysql-shell-660198.svg?style=flat)](https://galaxy.ansible.com/daixijun/mysql-shell/)
[![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/daixijun/ansible-role-mysql-shell?sort=semver)](https://github.com/daixijun/ansible-role-mysql-shell/tags)

## 环境要求

- CentOS 7
- Ansible 2.9+
- MySQL 8.0+

## 角色变量

- `mysqlshell_version`: 版本号
- `mysqlshell_ic_name`: Innodb Cluster 名称, 默认 "default"
- `mysqlshell_mysqlx_server`: MGR Primary 节点管理端口连接地址, 如: 172.17.0.2:33060
- `mysqlshell_admin_username`: InnoDB Cluster操作账号，需要具备所有权限及 with grant option
- `mysqlshell_admin_password`: 密码

## 依赖

- daixijun.mysql

## 示例

参考 [molecule](./molecule/default/converge.yml)

## License

BSD

## 作者信息

- Xijun Dai <daixijun1990@gmail.com>
