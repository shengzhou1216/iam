# 配置项目

## 安装 MariaDB

for `ubuntu 20.04`

1. 添加源
    ```bash
    sudo apt-get install software-properties-common dirmngr apt-transport-https
    sudo apt-key adv --fetch-keys 'https://mariadb.org/mariadb_release_signing_key.asc'
    sudo add-apt-repository 'deb [arch=amd64,arm64,ppc64el,s390x] https://mirrors.aliyun.com/mariadb/repo/10.7/ubuntu focal main'
    ```

2. 安装
   ```bash
    sudo apt update
    sudo apt install mariadb-server
   ```
