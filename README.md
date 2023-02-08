# Flight Tracker Microservice
## Individual Project 1 for IDS 721, Duke University

A simple Flask microservice to track flight status.

### Prerequisites
* Docker

### Usage
1. Clone the repository to your local machine.

```
$ git clone https://github.com/unsupervisedlearner1123/flight-status-track.git
```

2. Navigate into the project directory.

```
$ cd flight-status-track
```

3. Build the Docker image using the Dockerfile.

```
$ docker build -t [imagename] .
```

4. Run the Docker container.

```
$ docker run -e API_KEY=[your_api_key] [imagename]
```

5. Access the flight tracker microservice in your web browser at http://localhost:5000.

### Contributing

Contributions are welcome! Pleae open a pull request and I will respond at the earliest.



