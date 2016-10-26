# Usage

## Vagrant up

```
$ git clone https://github.com/duboviy/Vagrantfiles.git
$ cd Vagrantfiles/centos
$ vagrant up
```

## Build Docker image

```
$ docker build -t centos .
```

## Run Docker container

```
$ docker run -p 80:80 -v /vagrant:/vagrant -d centos
```

## Access to httpd container

http://192.168.33.10/
