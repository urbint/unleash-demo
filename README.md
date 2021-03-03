# unleash-demo

small demo for unleash feature flags

# Start by cloning this repository.
 
Small mono-repo , when cloning make sure the two main files are within the same file

# Navigate to file unleash-docker 

It is set up with `docker-compose` to start postgres and the unleash server together. This makes it really fast to start up
unleash locally without setting up a database or node.

```bash
$ docker-compose build
$ docker-compose up
```
