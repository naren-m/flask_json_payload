# Flask json payload

Example on how to use flask to receive json payload and store it in an object

## Build docker container

```sh
 docker build -t narenm/flask
 ```

## Start docker with code mounted

```bash

docker run -d --name flask -p 5000:5000 -v $PWD:/webapp narenm/flask:py3

or

./start_container.sh

```

## Reference

- [Flask Restful](https://flask-restful.readthedocs.io/en/0.3.5/)
