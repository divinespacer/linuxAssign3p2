# as3p2-starter-f23

You will have to edit some of these files to get your web servers working.

The included backend server runs on port 8080, 127.0.0.1:8080

## Included material

- example curl commands for testing your server, curl.md

# File Directories for server setup

## /var/www/backend

- backend binary, **hello-server**

## /var/www/my-site

- frontend, **index.html**

## /etc/nginx/sites-available

- nginx configuration file, **hello.conf**
- (also symbolic link to /etc/nginx/sites-enabled)

## /etc/systemd/system

- service file for backend, **hello-server.service**

## Digital Ocean Initialization Script

- config for setting up servers, **cloud-config.yml**
