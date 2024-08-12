# Writon API

This repository contains the Writon API, powered by Pocketbase. Below are the instructions to build and run the application using Docker.

## Documentation

For detailed documentation on Pocketbase, visit the [official Pocketbase documentation](https://pocketbase.io/docs/).


## 1. Build the Docker Image

To build the Docker image for the Writon API, run the following command:

```bash
docker build -t writon-api .
```

## 2. Run the Application

Once the image is built, you can run the application using Docker Compose:

```bash
docker-compose up
```

## 3. Access the Application
After running the application, you can access the following endpoints:

- REST API: http://0.0.0.0:8080/api/
- Admin UI: http://0.0.0.0:8080/_/

## 3. Use the Application!
To see writon-api documentation get in </> API Preview: ![api preview](/assets/images/image-1.png)
And check all available endpoints: <br /> ![available endpoints](/assets/images/image-2.png)
