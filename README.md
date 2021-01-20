# go-hello-world

## getting started

1. clone the repo
2. `cd go-hello-word`
3. `docker build -t go-hello-world .`
4. `docker run  -v LOCAL_PROJECT_DIR:/app -p 8080:80 -it go-hello-world`
5. In a browser, navigate to http://localhost:8080/