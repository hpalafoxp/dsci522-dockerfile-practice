# dsci522-dockerfile-practice
522 - Individual Assignment 2

In order to properly run this, make sure you have Docker installed and running and type the following bash commands:

```
docker pull hpalafoxp/dsci522-dockerfile-practice
```

```
docker run --rm -it -p 8888:8888 \\
  hpalafoxp/dsci522-dockerfile-practice \
  start-notebook.sh --NotebookApp.token='' --NotebookApp.password=''
```
