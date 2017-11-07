# Docker Jekyll Website


## Requirements:

- [Docker](https://docs.docker.com/engine/installation/)
- [Docker-compose](https://docs.docker.com/compose/install/)


## Setup:
1. Clone repository 

2. Install dependecies
    ```bash
    docker-compose run site bundle install
    ```
    
3. Start dev server
    ```bash
    docker-compose up
    ```

4. Open `http://localhost:4000`





## 

Developer server:
`docker-compose up`


Open container shell:
`docker-compose exec site bash`
