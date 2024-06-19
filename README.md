# InfluxDB Compose Example

This repository contains an example of using Docker Compose to set up an InfluxDB database.

## Prerequisites

Before running this example, make sure you have the following installed:

- Docker
- Docker Compose

## Usage

To start the InfluxDB container, run the following command:

```shell
docker-compose up -d
```

This will start the InfluxDB container in detached mode.

To stop the container, run the following command:

```shell
docker-compose down
```

## Configuration

The InfluxDB container is configured using environment variables. You can modify the `docker-compose.yml` file to change the configuration.

## Data Persistence

By default, the InfluxDB data is stored in a Docker volume named `influxdb_data`. This ensures that the data is persisted even if the container is stopped or removed.

## Accessing the InfluxDB UI

Once the container is running, you can access the InfluxDB UI by navigating to `http://localhost:8086` in your web browser.

## License

This example is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
