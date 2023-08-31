# ASCII Art Web Project

A web application that showcases ASCII art using Go templates.

## Features

- Displays various ASCII art banners.
- Built with Go templates for easy customization and extension.
- Dockerized for easy deployment and scaling.

## Getting Started

### Prerequisites
[Go](https://golang.org/doc/install)
[Docker](https://docs.docker.com/get-docker/)

### Running the Application
1. Clone the repository:
```bash
git clone https://learn.reboot01.com/git/mfaris/ascii-art-web-dockerize.git
cd ascii-art-web
```
2. Build the Docker image:
```bash
docker image build -f Dockerfile -t ascii-art .
```
3. Run the container:
```bash
docker container run -p 8080:8080 --detach --name server ascii-art
```
4. Access the web application at http://localhost:8080.

### Testing

To run the unit tests:

```bash
go test
```

### jLicense

This project is licensed under the MIT License and MeowCompany - see the LICENSE.md file for details.

