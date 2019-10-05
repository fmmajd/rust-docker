# Rust boilerplate project with docker

this is a simple template to start writing Rust programs.

I created this repository for myself, when I was starting to learn Rust and didn't want to install anything on my local machine.

if you are interested in using this template, simply clone it and then run:
```bash
docker-compose build
docker-compose up -d
```

and if/when you want to have access to the terminal, just run:
```bash
docker-compose exec rust bash
```

remember that the container's working directory is /home/rust

***if you want to rename the container, just uncomment the container_name line in docker-compose file***