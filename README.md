# Vulnerable-nginx

Vulnerable-nginx is an intentionally vulnerable NGINX setup that shows some common nginx misconfigurations. A blog post about the misconfigurations can be read here: [https://blog.detectify.com/2020/11/10/common-nginx-misconfigurations/](https://blog.detectify.com/2020/11/10/common-nginx-misconfigurations/)

## Installation

Requires docker

```bash
cd vulnerable-nginx
docker-compose up -d
```

## Usage

Visit http://localhost:5000/cats/ to get started (replace localhost with the ip of your docker-machine if you are using Docker Toolbox)