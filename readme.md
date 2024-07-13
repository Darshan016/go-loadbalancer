# Go Load Balancer

This is a simple load balancer implemented in Go, using round-robin scheduling to distribute incoming HTTP requests across multiple backend servers.

## Features

- Round-robin load balancing
- Reverse proxy using `net/http/httputil`
- Error handling


## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/Darshan016/go-loadbalancer.git
    cd go-loadbalancer
    ```

2. Build the project:

    ```sh
    go build -o loadbalancer
    ```

## Usage

1. Run the load balancer:

    ```sh
    ./loadbalancer
    ```

    By default, the load balancer will listen on port `8000`.

2. Send requests to the load balancer:

    You can use `curl` or any HTTP client to send requests to `http://localhost:8000`

