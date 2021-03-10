# Docker Container Config for RoR

> A docker container configuration for a Ruby on Rails application ready to use ;)

![image](https://user-images.githubusercontent.com/5160907/110696898-43b40d80-81b1-11eb-9d15-049e6470bd28.png)

This project is an empty RoR API application ready to use, which was created under a docker container. You will be able to run the app by setting up the container.

## Built With

- Ruby 2.6.6,
- Rails 6.1.3,
- Postgres 1.1
- Docker 3.1

## Live Demo

[Live Demo Link](https://livedemo.com)


## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites
- Docker (last-version)

Follow the instructions to install docker from [Docker hub](https://docs.docker.com/get-docker/), depending on the operating system you have.

### Install

- Verify Docker Engine is installed correctly by running the `hello-world` image.

        sudo docker run hello-world

### Setup
- Clone this repository to your local machine.

        git clone git@github.com:enelesmai/docker-container-for-ror.git

### Usage
To get the container up just type the next command in your terminal

    $ sudo docker-compose up -d

To verify the container is running type
    
    $ sudo docker ps

To see the logs emmited by the services

    $sudo docker logs -f

To check the application in your browser go to

    http://localhost:3000

### Run tests
    Not Implemented

### Deployment
    Not Implemented



## Authors

👤 **Author1**

- Github: [@enelesmai](https://github.com/enelesmai)
- Twitter: [@enelesmai](https://twitter.com/enelesmai)
- Linkedin: [in/xochitlselene](https://linkedin.com/in/xochitlselene)


## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- [Docker/docs](https://docs.docker.com/)
- [Juan Vqz Youtube Channel - Primeros pasos en Docker...](https://www.youtube.com/channel/UC9bsDBNvCZEEjrjFdFLtIYA)
- Ode to my Family <3

## 📝 License

This project is [MIT](lic.url) licensed.
