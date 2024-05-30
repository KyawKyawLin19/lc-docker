<h1 align="center">Docker</h1>

## What is Docker
- Docker is a software platform that uses containers to build, share and run applications.
- Container is  basically a lightweight virtual machine. It's a packaged isoloated unit consisting of software that you need to run your applications. Each container houses an operating system, necessary packages and potentially your applications source code in order for it to run.

## Docker command
```
docker ps
```
which will show any active containers in our system.

```
docker run --rm hello-world
```
remove the container

```
docker run --rm ubuntu:latest cat /etc/os-release
```