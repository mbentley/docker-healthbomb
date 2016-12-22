mbentley/healthbomb
===================

docker image for stressing docker health checks
based off of alpine:latest

To pull this image:
`docker pull mbentley/healthbomb`

Example usage:
`docker run -d --name healthbomb mbentley/healthbomb`

By default, this just runs a basic container that runs a ping command with a health check to make sure ping is running. The health check runs every 5 seconds with a 3 second timeout. Run multiple containers to stress an engine.
