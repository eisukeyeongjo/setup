# setup

### 01. Edit inventory file

```
$ cp inventory{.sample,}
$ vi inventory
```

### 02. Execute playbook
##### 02-01. for fedora server

```
$ ansible-playbook -i inventory playbooks/setup_fedora.yml
```

##### 02-01. for fedora server

```
$ ansible-playbook -i inventory playbooks/setup_fedora.yml
```

### 03. Install vim-plug manually from the target host

```
$ vim  -c 'PlugInstall'  -c q -c q
```