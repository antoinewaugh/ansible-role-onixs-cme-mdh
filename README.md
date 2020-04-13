# Role Name

An ansible role to fetch and install OnixS CME market data handler library.

# Requirements

None

# Role Variables

Default variables are as follows:

```
onixs_cme_mdh_os: 'CentOS'
onixs_cme_mdh_os_ver: '7'
onixs_cme_mdh_gcc_ver: '485'
onixs_cme_mdh_cpp_ver: '11'
onixs_cme_mdh_ver: '5.1.4'
onixs_cme_mdh_user: 'SECRET'
onixs_cme_mdh_password: 'XXXXXXXXXX'
onixs_cme_mdh_temp_dir: /tmp
onixs_cme_mdh_library_dir: /usr/local/lib/OnixS
onixs_cme_mdh_include_dir: /usr/local/include/OnixS
```

# Example Playbook

```
- hosts: 'all'
  roles:
  - role: 'onixs-cme-mdh'
    onixs_cme_mdh_os: 'CentOS'
    onixs_cme_mdh_os_ver: '6'
    onixs_cme_mdh_user: 'xxxx'
    onixs_cme_mdh_password: 'xxxxxxxxxxxxxx'
```

# Author information

Antoine Waugh (http://github.com/twanas)
