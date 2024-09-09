# nexus_ansible

.
├── ansible.cfg
├── defaults
│   └── main.yml
├── files
│   └── nexus.service
├── hellal server.pem
├── inventory
├── nexus
│   ├── defaults
│   │   └── main.yml
│   ├── files
│   ├── handlers
│   │   └── main.yml
│   ├── meta
│   │   └── main.yml
│   ├── README.md
│   ├── tasks
│   │   ├── install.yml
│   │   └── main.yml
│   ├── templates
│   ├── tests
│   │   ├── inventory
│   │   └── test.yml
│   └── vars
│       └── main.yml
├── nexus.yml
├── private-key
├── roles
│   └── nexus
│       ├── defaults
│       ├── files
│       ├── tasks
│       └── vars
├── tasks
│   ├── configure.yml
│   ├── install.yml
│   ├── main.yml
│   └── service.yml
├── templates
│   ├── nexus-default.properties.j2
│   ├── nexus-init.j2
│   ├── nexus.rc.j2
│   ├── nexus.service.j2
│   └── nexus.vmoptions.j2
└── vars
    └── main.yml
