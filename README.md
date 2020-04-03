# ios_upgrade_playbook
Ansible Playbook to upgrade IOS in Cisco routers
Using the tree command you can see the file structure I'm using

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


