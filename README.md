# Docker S3
A very basic Docker S3 container.

### To build the container
```
docker build -t ryanratcliff/fakes3 .
```

### Alternatively, the container can be pulled from Docker Registry
```
docker pull ryanratcliff/fakes3
```

# Example usages

### To startup as is
```
docker run -d ryanratcliff/fakes3
```

### To start up with specific port exposed
```
docker run -d p 7070:7070 ryanratcliff/fakes3
```
