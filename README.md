# Create-Docker-Image

Docker build command:
docker build -t simpleuiapp:1.0 .

Docker run command:
docker run -d --rm --name diego -p 4000:4000 simpleuiapp:1.0

To display in the browser:
localhost:4000
