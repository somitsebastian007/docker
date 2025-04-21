# docker Commands
docker run -d -p host_port:container_port image_name

# Check Docker Version
docker --version

# List Running Containers
docker ps
docker ps -a

# Pull an Image
docker pull image_name

# List Images
docker images

# Run a Container
docker run image_name

# Run in Detached Mode
docker run -d image_name

# Map Ports
docker run -d -p host_port:container_port image_name

# Name a Container
docker run -d --name container_name image_name

# Stop a Container
docker stop container_name_or_id

# Start a Container
docker start container_name_or_id

# Remove a Container
docker rm container_name_or_id
# Use -f to force-remove a running container:
docker rm -f container_name_or_id

# Remove an Image
docker rmi image_name

# View Container Logs
docker logs container_name_or_id

# Access a Container’s Shell
docker exec -it container_name_or_id /bin/bash