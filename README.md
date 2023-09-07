# curematch/node-angular

Docker image for Node.js automated UI tests.
Forked from markhobson/node-chrome

Includes:

* JDK 8
* Node.js 14.x
* Chrome (latest)

Forked from markhobson/docker-node-chrome:master

Available on [Docker Hub](https://hub.docker.com/r/markhobson/node-chrome/).

## Demo
See the [demo](demo) npm project to see how this Docker image can be used to run UI tests. The [run.sh](demo/run.sh) script builds the project within the latest version of this image on Docker Hub.

# HowTo
To build a new image run - `docker build -t curematch/node-angular .`
Should be pushed to Hub after the image is built.

