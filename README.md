Role Directory Structure

ansible-example-project/
├── hosts
├── site.yml
└── roles/
    └── wildfly/
        ├── tasks/main.yml
        ├── handlers/main.yml
        ├── defaults/main.yml
        ├── files/wildfly.service
        └── templates/standalone.xml
