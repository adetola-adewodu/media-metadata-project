# Media Metadata Project

## Docker Compose

To build and run the project using Docker Compose, use the following commands:

```sh
docker compose --file docker-compose.yml up --build -d
```

```sh
docker compose down -v    # Remove existing volume
```

# Use cases
    * Translate captions for video
    * Spam Filtering

## Ideas:

    * Use Open AI's Whisper library to insert and translate data into a database
    * Insert clips and image data into database
    * Agent and LLM


