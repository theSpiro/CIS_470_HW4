# "Hello, World!" flask-app.

## Getting Started
Clone the repo and run the following commands.

### Build the Docker Image
docker build -t hello_world .

### Run the Docker Container
docker run -p 5000:5000 hello_world

### Run the container using custom name
docker run --name <insert_your_custom_name_here> hello_world