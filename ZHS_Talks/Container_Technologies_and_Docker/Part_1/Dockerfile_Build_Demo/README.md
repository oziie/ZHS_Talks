# How to..?


In this demo, main point is create docker image from Dockerfile. After container run, a static site will be ready.


- To do this, first of all, create docker image with this command:

    ```docker build -t example-site .```

- Once images is created, run a container with this image:

   ```docker container run -d --name new_static_site -p 80:80 example-site```
