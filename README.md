With **check_docker** can use it to check and alert on

-  memory consumption in absolute units (bytes, kb, mb, gb) and as a percentage (0-100%)
   of the container limit.
-  CPU usages as a percentage (0-100%) of container limit.
-  automatic restarts performed by the docker daemon
-  container status, i.e. is it running?
-  container health checks are passing?
-  uptime, i.e. is it able to stay running for a long enough time?
-  the presence of a container or containers matching specified names
-  image version, does the running image match that in the remote registry?
-  image age, when was the image built the last time?
