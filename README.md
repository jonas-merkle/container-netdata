# container-netdata

A Docker Compose container setup for [NetData](https://www.netdata.cloud/).

## Table of contents

- [container-netdata](#container-netdata)
  - [Table of contents](#table-of-contents)
  - [Setup](#setup)
  - [License](#license)

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

## License

This project is licensed under the [GNU Lesser General Public License v3.0](https://www.gnu.org/licenses/lgpl-3.0.html) (LGPLv3). You are free to use, modify, and distribute this software under the terms specified in the LGPLv3.

See the [LICENSE](./LICENSE) file for more detailed information.