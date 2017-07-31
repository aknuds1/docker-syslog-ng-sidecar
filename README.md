# docker-syslog-ng-sidecar
Dockerfile for syslog-ng to run in a sidecar container logging to stdout. The purpose of this
Dockerfile is to build a Docker image that runs in a sidecar container, forwarding logs
from the main container to stdout so Kubernetes can pick up the logs.
