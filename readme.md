# Jib_Mavan_Npm

This app uses jib maven plugin to build docker images for npm project.

### build:

`mvn clean install jib:build -Ddocker.image.tag=2`

### pull

`docker pull roxnz/npm-jib:2`

### run

`docker run -i --rm roxnz/npm-jib:2`
