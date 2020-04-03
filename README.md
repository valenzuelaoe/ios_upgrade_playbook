# IOS_Upgrade_Playbook

Ansible Playbook to upgrade IOS in Cisco routers.<br>
I will continue to add to the repo as far as building the inventory file for different flavor of ios models.
<br>
<br>
Below is the file structure of the playbook:


```
└─ $ ▶ tree
.
├── ansible.cfg
├── ios_upgrade_devices.yml
├── roles
│   ├── post_verification
│   │   └── tasks
│   │       ├── ios_postchecks.yml
│   │       └── main.yml
│   ├── pre_verification
│   │   └── tasks
│   │       ├── ios_prechecks.yml
│   │       └── main.yml
│   └── upgrade
│       └── tasks
│           ├── ios_upgrade.yml
│           └── main.yml
└── vars
    └── ios_prechecks_vars.yml

8 directories, 9 files
```

