# Ansible Portfolio Website Deployment

A student project that uses Ansible to install Nginx and deploy a static portfolio website to an Ubuntu server.

## Features

- Installs Nginx using Ansible.
- Starts Nginx and enables it at boot.
- Deploys the portfolio website files to `/var/www/html/`.
- Includes Home, About, Projects, and Contact pages.
- Uses a shared CSS stylesheet.
- Restarts Nginx after the website files are deployed.

## Technologies

- HTML5
- CSS3
- Ansible
- Nginx
- Ubuntu Linux

## Project Structure

```text
Ansible_project_1/
├── inventory.ini
├── site.yml
└── roles/
    └── portfolio/
        ├── files/
        │   ├── about.html
        │   ├── contact.html
        │   ├── index.html
        │   ├── projects.html
        │   └── style.css
        ├── handlers/
        │   └── main.yml
        ├── tasks/
        │   └── main.yml
        ├── tests/
        │   └── test.yml
        └── vars/
            └── main.yml
