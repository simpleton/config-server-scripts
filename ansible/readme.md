### 1. add my pub key to server
```shell
./add_pub.sh
```

###2. disable login server by password
```shell
ansible-playbook ansible-lineinfile.yml -i ./hosts
```
