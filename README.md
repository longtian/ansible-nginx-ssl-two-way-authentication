# Ansible role to create nginx server with two way authentication 

### Requirements

- centos 6.5

### Usage

#### Install

```bash
ansible-playbook -i inventories/dev site.yml -u root -k
```

#### Add user certificate

```bash
ansible-playbook -i inventories/dev site.yml -u root -k --skip-tags cleanup
```


### Reference

- https://blog.imdst.com/nginx-ssl-shuang-xiang-ren-zheng-key-sheng-cheng-he-pei-zhi/