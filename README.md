# docker-syslog-ng-sidecar

This is a fork of [aknuds1/docker-syslog-ng-sidecar](https://github.com/aknuds1/docker-syslog-ng-sidecar)
updated with automated and tagged builds, and a newer version of Alpine.

Dockerfile for syslog-ng to run in a sidecar container logging to stdout. The purpose of this
Dockerfile is to build a Docker image that runs in a sidecar container, forwarding logs
from the main container to stdout so Kubernetes can pick up the logs.
