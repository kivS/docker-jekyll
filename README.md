# Docker Jekyll Website

## Default Components:
- Jekyll default theme - minima
- Jekyll feed plugin
- Jekyll Livereload plugin

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



## Utils

- Open container shell:
    ```bash
    docker-compose exec site bash
    ```
    
- Bundle folder location: `code/.vendor_bundle`

- Default theme location: `code/.vendor_bundle/gems/minima-X.X.X`
