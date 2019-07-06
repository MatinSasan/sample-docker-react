1.`docker build -f Dockerfile.dev .`

2.`docker run -p 3000:3000 -v \$(pwd):/app (dockerImageId)`

3.Added docker-compose to automate all these

> instead of \$(pwd) use absolute path for windows

## Import note for React on Docker:

If you are running on Windows, please read this: Create-React-App has some issues detecting when files get changed on Windows based machines. To fix this, please do the following:

In the root project directory, create a file `called .env`

Add the following text to the file and save it: `CHOKIDAR_USEPOLLING=true`

That's all!
