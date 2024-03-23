# actix-web-note

Just trying to learn actix-web by writing a notes application.

## Running the application

clone the repository and run the following commands:
```bash
git clone https://www.github.com/jiisanda/actix-web-note
```

start the postgresql server in the Docker container by running
```bash
docker-compose up -d
```

run ```cargo install sqlx-cli``` to install the SQLX-CLI if you do not already have it. Push `up` migrations scripts 
to the postgresql database by running ```sql migrate run```

Run ```cargo r -r``` to install the necessary crates and start the Actix-Web server.

Import the [postman_collection](web-actix-notes.postman_collection.json) into Postman or any API Client to test the CRUD 
API endpoints.
