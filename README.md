```
roles/
└── role_name/
    ├── tasks/         # Main tasks for this role (usually main.yml)
    ├── vars/          # Variables for this role (usually main.yml)
    ├── defaults/      # Default variables for this role (usually main.yml)
    ├── handlers/      # Handlers to notify on task changes
    ├── files/         # Static files used by the role
    ├── templates/     # Templates used by the role
    └── meta/          # Metadata about the role, including dependencies
```
