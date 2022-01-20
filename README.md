# Docker Compose example

The project aims to show and test a simple docker-compose command.

The application contains a simple "Hello World" exposed on the 5000 port of localhost.

Backend is written in Python and uses a Redis simple cache.

## Running the example

To fire the "web" and "redis" services, run:
```bash
docker-compose up
```

And via a web browser or curl, connect to ```http://localhost:5000```.
You can now see the "Hello World" message.

To stop both the services, type:

```
docker-compose down --volume # It stops and deletes the mounted volume with the latest updates
```

