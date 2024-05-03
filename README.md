

# LEMP Stack with WordPress on Ubuntu

This repository contains a Docker Compose configuration for setting up a LEMP (Linux, Nginx, MySQL, PHP) stack with WordPress on Ubuntu.

## Requirements

- Docker
- Docker Compose

## Instructions

1. Clone the repository:

   git clone https://github.com/dieterverbeek/wordpress-lemp.git
   

2. Navigate to the cloned directory:

   cd wordpress-lemp
   

3. Create the following directories:  (These directories are used to store Nginx logs, and data for WordPress and MySQL.)

   - sudo mkdir -p logs/
   - sudo mkdir -p logs/nginx
   - sudo mkdir -p data/
   - sudo mkdir -p data/html
   - sudo mkdir -p data/mysql


4. Start the containers:

   docker-compose up -d
   


## Configuration

- Nginx configuration files can be found in `nginx/conf.d/`.
- MySQL configuration files can be found in `mysql/`.
- WordPress files can be found in `data/html/`.

## Customization

You can customize the configuration as needed by modifying the YAML files in this repository.

Enjoy your LEMP stack with WordPress! For questions or issues, open an issue on GitHub.

