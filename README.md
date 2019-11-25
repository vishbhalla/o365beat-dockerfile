# Dockerfile for o365beat

### A docker file to build a ubuntu image with [O365beat](https://github.com/counteractive/o365beat)

### Build:

Edit o365beat.yml [as required](https://github.com/counteractive/o365beat/blob/master/o365beat.reference.yml).

Edit the [release version](https://github.com/counteractive/o365beat/releases) required in the Dockerfile, then:
```
# docker build -t o365beats .
# docker run -it o365beats
```
