# Ansible Web Server and Database Setup

This Ansible project sets up a web server and a database server. It includes variables, loops, conditionals (`when`), handlers, and roles.

## Project Structure
.
├── ansible.cfg
├── inventory
├── roles
│   ├── common
│   │   ├── handlers
│   │   │   └── main.yml
│   │   └── tasks
│   │       └── main.yml
│   ├── vars
│   │   └── main.yml
│   └── webserver
│       ├── tasks
│       │   └── main.yml
│       └── templates
│           └── index.html.j2
└── site.yml

 ## Terminologies
 1. **Handlers:** Handlers are tasks that are triggered by other tasks using the notify directive.
 2. **Roles:** Roles are a way to organize and reuse Ansible tasks, handlers, variables, and other components.
 3. **Templates:** Templates are files that contain variables and logic written in Jinja2 templating language.
