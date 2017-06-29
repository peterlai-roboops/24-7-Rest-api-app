docker build -t my-scala-container .
docker run -it --rm --name my-test-app my-scala-container
how to build it, incase you forget dumbo. 


docker run -it --rm -v ${PWD}:/app -w /app peterlai/restapi