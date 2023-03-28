# container-netdata

A Docker Compose container setup for [NetData](https://www.netdata.cloud/).

## Table of contents

- [container-netdata](#container-netdata)
  - [Table of contents](#table-of-contents)
  - [Setup](#setup)

## Setup

0. Requirements

   - Docker
   - Docker Compose

1. Add environment variables

    Add the missing information for the environment variables:

    ```bash
    nano .env
    ```

    Mark the `.env` file so they will not be tracked by git:

    ```bash
    git update-index --assume-unchanged .env
    ```

2. Start container

    ```bash
    docker-compose up --build -d
    ````

3. Stop container

    ```bash
    docker-compose down
    ```
