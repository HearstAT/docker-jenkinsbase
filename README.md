hearstat/jenkins-slave-base
================

Container to be utilized with the Jenkins Docker Plugin

## Latest Build Info
* Base Image: ubuntu:xenial
* openJDK: 8

## Trusty Build Info
* Base Image: ubuntu:trusty
* openJDK: 7

## Usage

```
FROM jenkins-slave-base:xenial
```

## Building

To build the image, do the following:

```
% docker build github.com/hearstat/docker-jenkinsbase
```

A prebuilt container is available in the docker index.

```
% docker pull hearstat/jenkins-slave-base
```
