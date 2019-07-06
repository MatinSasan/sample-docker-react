1. docker build -f Dockerfile.dev .

2. docker run -p 3000:3000 -v \$(pwd):/app (dockerImageId)

> instead of \$(pwd) absolute path for windows
