# Hello, Captain!

A simple Docker project that uses Alpine Linux to print `Hello, Captain!`.

## Requirements

* Docker
* Git

## How to Run

Clone the repository:

```bash
git clone https://github.com/Lochmoi/hello-captain.git
cd hello-captain
```

Build the Docker image:

```bash
sudo docker build -t hello-captain .
```

Run the Docker container:

```bash
sudo docker run --rm hello-captain
```

Expected output:

```text
Hello, Captain!
```

## Project URL

https://github.com/Lochmoi/hello-captain
