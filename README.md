## CentOS 7 C/C++ development environment with Homebrew support
* centos 7 with homebrew support, easy to use and maintain
* ship with gcc/g++ 5.5, boost 1.7+ and folly v2019.08.05.00

## Usage Example
1. start a container
```shell
docker run -d \
  -it \
  --name dev \
  -v /Volumes/Develop:/develop \
  centos-dev-brew:latest
```
2. enter the container
```shell
docker exec -it dev bash
```
3. enjoy coding
* libs are located at ~/.linuxbrew/lib and ~/.linuxbrew/include
* use 'brew install' to install package you want
