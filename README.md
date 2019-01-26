
This image is a Jenkins slave with Docker installed, for use with the
`docker-slaves` Jenkins plugin when the build itself also needs to launch
containers. You can configure the plugin so that Docker launches those
containers as siblings of the slave container on the host.

Docker Hub autobuild is enabled for Git tags matching `^v(\d+\.\d+\.\d)$`,
where the Docker tags will be `latest` and the capture group.
